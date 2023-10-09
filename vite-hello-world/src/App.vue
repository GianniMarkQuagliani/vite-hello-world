<!-- ************************************ SCRIPT ************************************ -->
<script>
// Import
import Header from './components/Header.vue';

// Export
export default {
  nome: 'App',

  // Components
  components: {
    Header
  },

  // Data
  data() {
    return {
      titolo : 'La mia prima app con Vite!'
    }
  },
}
</script>


<!-- ************************************ TEMPLATE ************************************ -->
<template>
  <main>
    <h1>{{ titolo }}</h1>
  </main>
  
</template>


<!-- ************************************ STYLE ************************************ -->
<style>

</style>
