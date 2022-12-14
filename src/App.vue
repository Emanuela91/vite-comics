<script>
import HeaderVue from './components/Header.vue';
import FooterVue from './components/Footer.vue';
import JumbotronVue from './components/Jumbotron.vue';
import MainVue from './components/Main.vue';

export default {
  name: "App",
  components: {
    HeaderVue,
    JumbotronVue,
    MainVue,
    FooterVue,
  }
}
</script>

<template>
  <HeaderVue />
  <main>
    <JumbotronVue />
    <MainVue />
  </main>
  <FooterVue />
</template>

<style lang="scss">
@use './styles/general.scss' as*;
@use './styles/partials/variables' as*;
</style>
