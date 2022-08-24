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
 @import "~/node_modules/bootstrap/scss/bootstrap.scss";
 @import "./styles/variables.scss";
 @import "./styles/general.scss"
}
</style>
