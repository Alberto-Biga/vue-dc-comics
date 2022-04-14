<template>
  <div id="app">    
    <NavComp/>
    <MainComp/>
    <InfoComp/>
  </div>
</template>

<script>
import NavComp from './components/NavComp.vue'
import MainComp from './components/MainComp.vue'
import InfoComp from './components/InfoComp.vue'

export default {
  name: 'App',
  components: {
    NavComp,
    MainComp,
    InfoComp
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
*{
    margin: 0;
}
</style>
