<script>

import PrimoComponent from './components/PrimoComponent.vue'

export default {
  name: 'App',
  components:{
    PrimoComponent
  },
  data(){
    return{
      titolo: 'Ciao Vue Vite da data'
    }
  }
}
</script>

<template>

  <div class="container">
    <h1>{{titolo}}</h1>
    <h2>Sono un H2</h2>
  </div>
  <PrimoComponent />
    
</template>


<style>

</style>