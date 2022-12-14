<script>
import HeaderVue from './components/Header.vue';
import FooterVue from './components/Footer.vue';

export default {
  name: "App",
  components: {
    HeaderVue,
    FooterVue
  }
}
</script>

<template>
  <HeaderVue />
  <main>
    <div class="container">
      <h1>Content goes here!</h1>
    </div>
  </main>
  <FooterVue />
</template>

<style lang="scss">
@use './styles/general.scss' as*;
@use './styles/partials/variables' as*;
</style>
