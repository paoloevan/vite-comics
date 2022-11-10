
<!--
Create un nuovo progetto utilizzando Vite e Vue 3 e definite i componenti
necessari per strutturare il layout come da screenshot allegato.
Quando la struttura a macroblocchi è pronta, popolate le voci di menu dinamicamente usando i data del componente. -->

<script>

import AppHeader from './components/AppHeader.vue';
import Main from './components/Main.vue';
import Footer from './components/Footer.vue';

export default {
  name: 'App',
  components: {
    AppHeader,
    Main,
    Footer
  }
}
</script>

<template>

  <AppHeader />
  <Main />
  <Footer />
</template>

<style>

</style>