<template>
  <div id="app">
    <img class="img" alt="Vue logo" src="./assets/logo.png">
    <MonacoEditor />
  </div>
</template>

<script>
import MonacoEditor from './components/MonacoEditor.vue'

export default {
  name: 'app',
  components: {
    MonacoEditor
  }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #2c3e50;
  margin-top: 60px;
}
.img {
  display: block;
  margin: 0 auto;
}
</style>
