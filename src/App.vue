<template>
  <div id="app">
    <maintenance/>
  </div>
</template>

<script>
// import HelloWorld from './components/HelloWorld.vue'
import Maintenance from './components/Maintenance.vue'

export default {
  name: 'App',
  components: {
    // HelloWorld
    Maintenance
  },
  metaInfo: {
      // if no subcomponents specify a metaInfo.title, this title will be used
      title: 'Default Title',
      // all titles will be injected into this template
      titleTemplate: '%s | My Awesome Webapp'
    }

}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
