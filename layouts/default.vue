<template>
  <div class="has-navbar-fixed-top">
    <HeaderSection />
    <Nuxt />
  </div>
</template>

<script>
import HeaderSection from '../components/header/HeaderSection.vue';

export default {
  components: {
    HeaderSection
  }
}
</script>

<style>
html {
  scroll-behavior: smooth;
}
</style>
