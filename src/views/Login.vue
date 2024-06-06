<template>
    <div class="container-login shadow p-3 mb-5 row form-group">
        <small class="title pb-3">Login de administrador</small>
        <div class="row-sm pb-3">
            <input type="email" class="form-control rounded-pill border border-dark-subtle" id="inputEmail"
                placeholder="E-mail">
        </div>
        <div class="row-sm pb-4">
            <input type="password" class="form-control rounded-pill border border-dark-subtle" id="inputPassword"
                placeholder="Senha">
        </div>
        <div class="row-sm pb-3">
            <button @click="goToDashboard" class="btn login-button rounded-pill">Acessar</button>
        </div>
    </div>
</template>
<script>
import axios from 'axios'

export default {
    methods: {
        goToDashboard() {
            axios.post('http://localhost:8000/api/login', {
                email: document.getElementById('inputEmail').value,
                password: document.getElementById('inputPassword').value
            }).then(response => {
                localStorage.setItem('token', response.data)

                axios.defaults.headers.common[ 'Authorization' ] = 'Bearer ' + localStorage.getItem('token');

                this.$router.push('/dashboard');
            }).catch(error => {
                console.log(error)
            });
        }
    }

}
</script>
<style scoped>
body {
    display: flex;
    align-items: center;
}

.title {
    font-size: 1rem;
    font-weight: 600;
    margin-bottom: 1rem;
    color: #ec631a;
    font-family: "Montserrat", sans-serif;
    font-optical-sizing: auto;
}

::-webkit-input-placeholder {
    color: gray;
    font: 12px verdana, arial, sans-serif;
}

.container-login {
    max-width: 390px;
}

.login-button {
    color: white;
    background-color: #ec631a;
    width: 100%;
}
</style>