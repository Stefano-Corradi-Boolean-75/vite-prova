<script>
export default {
  name: 'PrimoComponent',
  data(){
    return{
      titolo: 'sono il titolo del componente'
    }
  }
}
</script>

<template>
  <div class="container">
    <h2>{{titolo}}</h2>
  </div>
</template>



<style scoped>
h2{
  color: red;
}
</style>