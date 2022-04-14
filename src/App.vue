<template>
  <div id="app">    
    <NavComp/>
    <MainComp/>
  </div>
</template>

<script>
import NavComp from './components/NavComp.vue'
import MainComp from './components/MainComp.vue'

export default {
  name: 'App',
  components: {
    NavComp,
    MainComp
  }
}
</script>

<style lang="scss">
#app {  
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  // text-align: center;
  color: #2c3e50;  
}
</style>
