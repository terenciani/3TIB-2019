<template>
    <div>
        <h1>Bem-vindo {{usuario}}</h1>

        <h2>{{usuario}}</h2>

        <input v-model="usuario">

        <button @click="realizarLogin">Logar</button>
    </div>
</template>
<script>
    export default{
        data(){
            return{
                usuario: "Guilherme"
            }
        },
        methods:{
            realizarLogin(){
                if(this.usuario == "Guilherme"){
                    console.log("è o bicho da batata")
                }else{
                    console.log("Não è o bicho da batata, é o bigato")
                }
            }
        }
    }
</script>
<style>

</style>