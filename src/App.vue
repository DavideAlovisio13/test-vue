<template>
  <HeaderComponent />
  <MainComponent />
</template>

<script>
import HeaderComponent from './components/HeaderComponent.vue'; // importo il componente
import MainComponent from './components/MainComponent.vue'; // importo il componente
  export default {
    name: 'App',// meglio che gli dò un nome a questo componente
    components: {
      HeaderComponent, // importo il componente dichiarandolo come oggetto 
      MainComponent // importo il componente dichiarandolo come oggetto
    },
    data() {
      return {
        
      }
    }
  }
</script>

<style scoped>
</style>