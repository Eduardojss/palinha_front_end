<script setup>
import Login from './views/Login.vue'
import Navbar from './components/Navbar.vue'
</script>

<template>
  <div class="container flex-start montserrat">
    <Navbar />
    <router-view />
  </div>
</template>
<script>
import axios from 'axios'
export default{
  mounted(){
    let token = localStorage.getItem('token')
    if(localStorage.getItem('token')){
      axios.defaults.headers.common[ 'Authorization' ] = 'Bearer ' + token;
    }else{
      axios.defaults.headers.common[ 'Authorization' ] = null;
    }
  }
}
</script>
