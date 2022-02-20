<template>
    <main>
        <Sobre/>
        <MaisInformacoes/> 
        <section class="contato">

        </section>
    </main>
</template>

<script>
import Sobre from "./Sobre.vue";
import MaisInformacoes from "./MaisInformacoes.vue";
export default{
    name: "Main",
    components:{
        Sobre,
        MaisInformacoes
    }
}
</script>

<footer>

</footer>
