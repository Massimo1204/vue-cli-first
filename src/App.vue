<template>
  <div id="app">
    <indexTitle/>
    <indexJumbo/>
  </div>
</template>

<script>
import indexTitle from './components/title.vue'
import indexJumbo from './components/hero.vue'

export default {
  name: 'App',
  components: {
    indexTitle,
    indexJumbo
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
