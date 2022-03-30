<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <HelloWorld msg="Welcome to Your Vue.js App"/>
    <span>Inline</span>
    <IconWord />
    <span>External</span>
    <img src="./assets/icon-word.svg" />
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import IconWord from './assets/icon-word.svg?inline'

export default {
  name: 'App',
  components: {
    HelloWorld,
    IconWord
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
