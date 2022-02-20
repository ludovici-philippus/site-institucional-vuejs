<template>
  <router-view/>
</template>

<script>
export default{
    name: "App",
    data(){
        return{
        nome_empresa: "Based Empresa", 
        }    
    }
}
</script>

<style>
*{
margin: 0;
padding: 0;
box-sizing: border-box;
}
</style>
