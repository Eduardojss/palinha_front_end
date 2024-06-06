<template>
    <div class="container downloads text-start wrap">
        <div class="row mb-3">
            <small class="col-6 col-sm-8 col-lg-9 col-xl-10 text-left text-purple fw-bold">DOWNLOADS</small>
            <select class="col-6 col-sm-4 col-lg-3 col-xl-2 form-select" id="floatingSelect"
                style="background-color: #E44A16;color: white; font-size: 12px; width: 130px;">
                <option selected>Desde o Ínicio</option>
                <option value="1">7 Dias</option>
                <option value="2">30 Dias</option>
                <option value="3">3 Meses</option>
                <option value="3">6 Meses</option>
            </select>
        </div>
        <div class="row mb-3">
            <div class="col-12 col-md-4">
                <div class="p-3 shadow rounded d-flex flex-sm-row flex-md-column">
                    <div class="fs-1 fw-bold text-purple pe-2 text-responsive">{{ downloads }}</div>
                    <div class="fw-semibold text-orange">TOTAL DOWNLOADS</div>
                </div>
            </div>
            <div class="col-12 col-md-4">
                <div class="p-3 shadow rounded d-flex flex-sm-row flex-md-column">
                    <div class="fs-1 fw-bold text-purple pe-2 text-responsive">{{ ios }}</div>
                    <div class="fw-semibold text-orange">TOTAL IOS</div>
                </div>
            </div>
            <div class="col-12 col-md-4">
                <div class="p-3 shadow rounded d-flex flex-sm-row flex-md-column">
                    <div class="fs-1 fw-bold text-purple pe-2 text-responsive">{{ android }}</div>
                    <div class="fw-semibold text-orange">TOTAL ANDROID</div>
                </div>
            </div>
        </div>
        <div class="row mb-3">
            <div class="col-12 col-md-6">
                <div class="px-3 shadow rounded" style="height: 120px;">
                    <div class="row pt-4 pt-md-0">
                        <div class="col-6">
                            <p class="col-6 porcentagem fw-bold text-cyan">100<small class="fs-4">%</small></p>
                            <p class="text-cyan fw-semibold">Conversão</p>
                        </div>
                        <div class="col-6 mt-2">
                            <p class="fs-1 fw-bold text-purple text-center text-responsive">{{ acessos }}</p>
                            <p class="fw-semibold text-orange text-center negative-margin">ACESSOS IOS</p>
                        </div>
                    </div>
                </div>
            </div>
            <div class="col-12 col-md-6">
                <div class="px-3 shadow rounded" style="height: 120px;">
                    <div class=" row pt-4 pt-md-0">
                        <div class="col-6">
                            <p class="col-6 porcentagem fw-bold text-cyan">100<small class="fs-4">%</small></p>
                            <p class="text-cyan fw-semibold">Conversão</p>
                        </div>
                        <div class="col-6 mt-2">
                            <p class="fs-1 fw-bold text-purple text-center text-responsive">{{ acessos }}</p>
                            <p class="fw-semibold text-orange text-center negative-margin">ACESSOS IOS</p>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>
    <div class="container acessos text-start text-black wrap">
        <div class="row mb-3">
            <small class="col-6 col-sm-8 col-lg-9 col-xl-10 text-left text-purple fw-bold">ACESSOS WEB | TRÁFEGO EM
                USUÁRIOS ÚNICOS</small>
            <select class="col-6 col-sm-4 col-lg-3 col-xl-2 form-select" id="floatingSelect"
                style="background-color: #E44A16;color: white; font-size: 12px; width: 130px;">
                <option selected>Desde o Ínicio</option>
                <option value="1">7 Dias</option>
                <option value="2">30 Dias</option>
                <option value="3">3 Meses</option>
                <option value="3">6 Meses</option>
            </select>
        </div>
        <div class="row row-cols-1 mb-3">
            <div class="col-12">
                <div class="p-3 rounded bg-purple d-flex flex-md-row">
                    <div class="fs-1 fw-bold text-white pe-2 text-responsive">{{ acessos }}</div>
                    <div class="fw-semibold text-white pt-sm-0 pt-md-4">palinha.com.br</div>
                </div>
            </div>
        </div>
    </div>
    <div class="container downloads text-start wrap">
        <div class="row mb-3">
            <small class="col-6 col-sm-8 col-lg-9 col-xl-10 text-left text-purple fw-bold">DOWNLOADS</small>
            <select class="col-6 col-sm-4 col-lg-3 col-xl-2 form-select" id="floatingSelect"
                style="background-color: #E44A16;color: white; font-size: 12px; width: 130px;">
                <option selected>Desde o Ínicio</option>
                <option value="1">7 Dias</option>
                <option value="2">30 Dias</option>
                <option value="3">3 Meses</option>
                <option value="3">6 Meses</option>
            </select>
        </div>
        <div class="row mb-3">
            <div class="col-12 col-md-4">
                <div class="p-3 shadow rounded d-flex flex-sm-row flex-md-column">
                    <div class="fs-1 fw-bold text-cyan pe-2 text-responsive">{{ musicos }}</div>
                    <div class="fw-semibold text-cyan">TOTAL DE CADASTROS</div>
                </div>
            </div>
            <div class="col-12 col-md-4">
                <div class="p-3 shadow rounded d-flex flex-sm-row flex-md-column">
                    <div class="fs-1 fw-bold text-cyan pe-2 text-responsive">{{ musicosAtivos }}</div>
                    <div class="fw-semibold text-cyan">MÚSICOS ATIVOS</div>
                </div>
            </div>
            <div class="col-12 col-md-4">
                <div class="p-3 shadow rounded d-flex flex-sm-row flex-md-column">
                    <div class="fs-1 fw-bold text-cyan pe-2 text-responsive">{{ perfisCompletos }}</div>
                    <div class="fw-semibold text-cyan">PERFIS COMPLETOS</div>
                </div>
            </div>
        </div>
        <div class="row mb-3">
            <div class="col-12 col-md-6">
                <div class="px-3 shadow rounded bg-orange">
                    <div class="row">
                        <div class="col-6">
                            <p class="col-6 porcentagem fw-bold text-white ps-sm-4 ps-md-0">+100<small
                                    class="fs-4">%</small></p>
                            <p class="text-white fw-semibold text-center">PORCENTAGEM <br> DE CADASTROS</p>
                        </div>
                        <div class="col-6 mt-2">
                            <p class="fs-1 fw-bold text-white text-responsive">{{ compCadastros }}</p>
                            <p class="fs-20 text-white negative-margin">Cadastros comparados ao mesmo período anterior
                            </p>
                        </div>
                    </div>
                </div>
            </div>
            <div class="col-12 col-md-6">
                <div class="px-3 shadow rounded bg-orange">
                    <div class="row">
                        <div class="col-6 gx-2">
                            <p class="col-6 porcentagem fw-bold text-white ps-sm-4 ps-md-0">-100<small
                                    class="fs-4">%</small></p>
                            <p class="text-white fw-semibold text-center">PORCENTAGEM <br> DE CHURN</p>
                        </div>
                        <div class="col-6 mt-2">
                            <p class="fs-1 fw-bold text-white text-responsive">{{ compInativos }}</p>
                            <p class="fs-20 text-white negative-margin">Contas de músicos excluídas ou desativadas</p>
                        </div>
                    </div>
                </div>
            </div>
        </div>
        <div class="btn text-white bg-orange">
            MAIS DETALHES
        </div>
    </div>
    <div class="container mt-4 downloads text-start wrap">
        <div class="row mb-3">
            <small class="col-6 col-sm-8 col-lg-9 col-xl-10 text-left text-purple fw-bold">DOWNLOADS</small>
            <select class="col-6 col-sm-4 col-lg-3 col-xl-2 form-select" id="floatingSelect"
                style="background-color: #E44A16;color: white; font-size: 12px; width: 130px;">
                <option selected>Desde o Ínicio</option>
                <option value="1">7 Dias</option>
                <option value="2">30 Dias</option>
                <option value="3">3 Meses</option>
                <option value="3">6 Meses</option>
            </select>
        </div>
        <div class="row mb-3">
            <div class="col-12 col-md-6">
                <div class="px-3 shadow rounded bg-purple">
                    <div class="row">
                        <div class="col-6">
                            <p class="col-6 porcentagem fw-bold text-white ps-sm-4 ps-md-0">+100<small
                                    class="fs-4">%</small></p>
                            <p class="text-white fw-semibold text-center">PESSOA FISICA</p>
                        </div>
                        <div class="col-6 mt-2">
                            <p class="fs-1 fw-bold text-white text-responsive">{{ contratantesFisicos }}</p>
                            <p class="fs-20 text-white negative-margin">Cadastros comparados ao mesmo período anterior
                            </p>
                        </div>
                    </div>
                </div>
            </div>
            <div class="col-12 col-md-6">
                <div class="px-3 shadow rounded bg-purple">
                    <div class=" row">
                        <div class="col-6">
                            <p class="col-6 porcentagem fw-bold text-white ps-sm-4 ps-md-0">-100<small
                                    class="fs-4">%</small></p>
                            <p class="text-white fw-semibold text-center">PESSOA JURÍDICA</p>
                        </div>
                        <div class="col-6 mt-2">
                            <p class="fs-1 fw-bold text-white text-responsive">{{ contratantesJuridicos }}</p>
                            <p class="fs-20 text-white negative-margin">Cadastros comparados ao mesmo período anterior
                            </p>
                        </div>
                    </div>
                </div>
            </div>
        </div>
        <div class="btn text-white bg-orange">
            MAIS DETALHES
        </div>
    </div>
    <div class="container mt-4 downloads text-start wrap">
        <div class="row mb-3">
            <small class="col-6 col-sm-8 col-lg-9 col-xl-10 text-left text-purple fw-bold">DOWNLOADS</small>
            <select class="col-6 col-sm-4 col-lg-3 col-xl-2 form-select" id="floatingSelect"
                style="background-color: #E44A16;color: white; font-size: 12px; width: 130px;">
                <option selected>Desde o Ínicio</option>
                <option value="1">7 Dias</option>
                <option value="2">30 Dias</option>
                <option value="3">3 Meses</option>
                <option value="3">6 Meses</option>
            </select>
        </div>
        <div class="row mb-3">
            <div class="col-12 col-md-4">
                <div class="p-3 shadow rounded d-flex flex-sm-row flex-md-column">
                    <div class="fs-1 fw-bold text-purple pe-2 text-responsive">{{
                        contratos }}</div>
                    <div class="fw-semibold text-orange">CONTRATAÇÕES</div>
                </div>
            </div>
            <div class="col-12 col-md-4">
                <div class="p-3 shadow rounded d-flex flex-sm-row flex-md-column">
                    <div class="fs-1 fw-bold text-purple pe-2 text-responsive">{{
                        faturamento }}</div>
                    <div class="fw-semibold text-orange">TOTAL FATURADO</div>
                </div>
            </div>
            <div class="col-12 col-md-4">
                <div class="p-3 shadow rounded d-flex flex-sm-row flex-md-column">
                    <div class="fs-1 fw-bold text-purple pe-2 text-responsive">
                        1000000000000000000</div>
                    <div class=" fw-semibold text-orange">% APP</div>
                </div>
            </div>
        </div>
        <div class="row mb-3">
            <div class="col-12">
                <div class="px-3 shadow rounded bg-cyan">
                    <div class="row">
                        <div class="col-4">
                            <p class="porcentagem fw-bold text-white text-center text-responsive">-{{ gateway }}<small
                                    class="fs-4">%</small></p>
                            <p class="text-white fw-semibold text-center">Custo Gateway</p>
                        </div>
                        <div class="col-4 mt-2">
                            <p class="fs-1 fw-bold text-white text-center text-responsive">-{{ fiscal }}<small
                                    class="fs-4">%</small>
                            </p>
                            <p class="text-white fw-semibold text-center">Custo Fiscal</p>
                        </div>
                        <div class="col-4 mt-2">
                            <p class="fs-1 fw-bold text-white text-center text-responsive">{{ lucroReal }}</p>
                            <p class="text-white fw-semibold text-center">Lucro Real</p>
                        </div>
                    </div>
                </div>
            </div>
        </div>
        <div class="btn text-white bg-orange">
            MAIS DETALHES
        </div>
    </div>
</template>
<script>
import { ref } from 'vue';
import axios from 'axios'
export default {
    data() {
        return {
            downloads: 0,
            ios: 0,
            android: 0,
            acessos: 0,
            musicos: 0,
            musicosAtivos: 0,
            compCadastros: 0,
            compInativos: 0,
            perfisCompletos: 0,
            contratantesFisicos: 0,
            contratantesJuridicos: 0,
            contratos: 0,
            faturamento: 0,
            percentApp: 0,
            gateway: 0,
            fiscal: 0,
            lucroReal: 0,
            fontSize: 16,
        };
    },
    mounted() {
        this.adjustFontSize();

        axios.get('http://localhost:8000/api/dashboard').then(response => {
            this.downloads = response.data.data.downloads;
            this.ios = response.data.data.ios;
            this.android = response.data.data.android;
            this.acessos = response.data.data.acessos;
            this.musicos = response.data.data.musicos;
            this.musicosAtivos = response.data.data.musicosAtivos;
            this.perfisCompletos = response.data.data.perfisCompletos;
            this.contratantesFisicos = response.data.data.contratantesFisicos;
            this.contratantesJuridicos = response.data.data.contratantesJuridicos;
            this.contratos = response.data.data.contratos;
            this.faturamento = response.data.data.faturamento;
            this.percentApp = response.data.data.percentApp;
            this.gateway = response.data.data.gateway;
            this.fiscal = response.data.data.fiscal;
            this.lucroReal = response.data.data.lucroReal;
        }).catch(error => {
            console.log(error)
        });
    },
    methods: {
        adjustFontSize() {
            const div = this.$refs.textdiv
            while (div.scrollWidth > div.offsetWidth) {
                this.fontSize-- // Diminui o tamanho da fonte se o texto for maior que a div
            }
        },
    },
}
</script>
<style>
body {
    align-items: flex-start !important;
    padding-top: 4rem;
}

.downloads {
    width: 70vw;
    color: white;
    font-family: "Montserrat", sans-serif;
    font-optical-sizing: auto;
}

.text-purple {
    color: #803586;
}

.bg-purple {
    background-color: #803586;
}

.text-orange {
    color: #E44A16;
}

.bg-orange {
    background-color: #E44A16;
}

.negative-margin {
    margin-top: -4%;
}

.text-cyan {
    color: #32A071;
}

.bg-cyan {
    background-color: #32A071;
}

.porcentagem {
    font-size: 5vw;
    margin-bottom: -9%;
}

.fs-1 {
    font-size: 3.5vw !important;
    margin-bottom: 0%;
}

.fs-20 {
    font-size: 12px !important;
}

.no-border-btn {
    border: none;
}

.bg-purple {
    background-color: #803586;
}

.acessos {
    width: 70vw;
    color: white;
    font-family: "Montserrat", sans-serif;
    font-optical-sizing: auto;
}

.text-responsive {
    overflow: auto;
}
</style>