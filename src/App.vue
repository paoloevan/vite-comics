
<!--
Create un nuovo progetto utilizzando Vite e Vue 3 e definite i componenti
necessari per strutturare il layout come da screenshot allegato.
Quando la struttura a macroblocchi è pronta, popolate le voci di menu dinamicamente usando i data del componente. -->

<script>

import AppHeader from './components/AppHeader.vue';
import SiteMain from './components/SiteMain.vue';
import SiteFooter from './components/SiteFooter.vue';

export default {
  name: 'App',
  components: {
    AppHeader,
    SiteMain,
    SiteFooter
  }
}
</script>

<template>

  <AppHeader />
  <SiteMain />
  <SiteFooter />
</template>

<style>

</style>