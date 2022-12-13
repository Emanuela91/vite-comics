<script>
import HeaderVue from './components/Header.vue';

export default {
  name: "App",
  components: {
    HeaderVue,
  }
}
</script>

<template>
  <HeaderVue />
  <main>
    <h1>Content goes here!</h1>
  </main>
</template>

<style lang="scss">
@use './styles/general.scss' as*;
@use './styles/partials/variables' as*;
</style>
