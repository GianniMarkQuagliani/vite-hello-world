<!-- ************************************ SCRIPT ************************************ -->
<script>
// Import
import AppTitle from './components/AppTitle.vue';
import AppHero from './components/AppHero.vue';

// Export
export default{
  components: {
    AppTitle,
    AppHero
  }
}
</script>


<!-- ************************************ TEMPLATE ************************************ -->
<template>
  <div id="app">
    <AppTitle />
    <AppHero />
  </div>
</template>


<!-- ************************************ STYLE ************************************ -->
<style scoped>

</style>
