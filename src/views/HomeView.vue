<template>
    <Header/>
    <Main/>
    <Footer/>
</template>

<script>
import Header from "../components/Header.vue";
import Main from "../components/Main.vue";
import Footer from "../components/Footer.vue";

export default {
  name: 'HomeView',
  components: {
    Header,
    Main,
    Footer
  }
}
</script>
