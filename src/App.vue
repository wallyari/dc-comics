<template>
  <div id="app">
    
    <headerMain/>
  </div>
</template>

<script>
import headerMain from './components/header.vue'
import mainContent from './components/main.vue'
import  footerMain from './components/footer.vue'

export default {
  name: 'App',
  components: {
    headerMain,
    mainContent,
    footerMain,
  }
}
</script>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
