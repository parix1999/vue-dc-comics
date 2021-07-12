<template>
  <div id="app">
    <NavBar />
    <Content />
    <BarraAzzurra />
    <Footer />
    <BarraIscrizione /> 

  </div>
</template>

<script>
import NavBar from './components/Nav-bar.vue';
import Content from './components/Content.vue';
import BarraAzzurra from './components/Barra-azzurra.vue';
import Footer from './components/Footer.vue';
import BarraIscrizione from './components/Barra-iscrizione.vue';


export default {
  name: 'App',
  components: {
    NavBar,
    Content,
    BarraAzzurra,
    Footer,
    BarraIscrizione,


  }
}
</script>

<style lang="scss">

</style>
