<script>
import HeaderVue from './components/Header.vue';
import FooterVue from './components/Footer.vue';

export default {
  name: "App",
  components: {
    HeaderVue,
    FooterVue,
  }
}
</script>

<template>
  <div class="container">
    <HeaderVue />
    <main>
      <h1>Content goes here!</h1>
    </main>
    <FooterVue />
  </div>
</template>

<style lang="scss">
@use './styles/general.scss' as*;
@use './styles/partials/variables' as*;
</style>
