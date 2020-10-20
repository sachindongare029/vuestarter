<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <TodoHeader msg="Welcome to Vue.js App"/>
  </div>
</template>

<script>
import TodoHeader from './components/TodoHeader.vue'

export default {
  name: 'App',
  components: {
    TodoHeader
  }
}
</script>

<style>
body {
  height: 100vh;
  background: #a9a9a9;
}
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
