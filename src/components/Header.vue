<template>
  <header>
    <h1>{{title}}</h1>
  </header>
</template>

<script>
  export default {
    name: "Header",
    data(){
      return {
        title : 'Vue.js Demo'
      }
    }
  }
</script>

<style scoped>
  h1 {
    color: lightblue;
    padding: 10px;
  }
</style>
