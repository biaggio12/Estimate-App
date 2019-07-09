<template>
  <div id="app">
    <NavBar />
    <Content />
  </div>
</template>

<script>

import NavBar from './components/NavBar.vue'
import Content from './components/Content.vue'
export default {
  name: 'app',
  components: {
    NavBar,
    Content,
  },
  data: function() {
      return {}
  }
}
</script>

<style lang="scss">
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
