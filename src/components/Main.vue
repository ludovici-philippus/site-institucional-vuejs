<template>
    <main>
        <Sobre/>
        <MaisInformacoes/> 
        <Contato/>
    </main>
</template>

<script>
import Sobre from "./Sobre.vue";
import MaisInformacoes from "./MaisInformacoes.vue";
import Contato from "./Contato.vue";
export default{
    name: "Main",
    components:{
        Sobre,
        MaisInformacoes,
        Contato
    }
}
</script>

<footer>

</footer>
