<template>

<Banner />    
<ConteudoPrincipal />
<Rodape />
</template>

<script lang="ts">
import Banner from './components/Banner.vue'
import ConteudoPrincipal from './components/ConteudoPrincipal.vue'
import Rodape from './components/Rodape.vue';

export default {
  name: 'App',
  components: {
    Banner,
    ConteudoPrincipal,
    Rodape
  }
}
</script>

<style scoped>
</style>