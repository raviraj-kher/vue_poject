<template>
  <img alt="Vue logo" src="./assets/logo.png">
  <!-- <HelloWorld msg="Welcome to Your Vue.js App"/> -->
  <index />
  <formElement />
</template>

<script>
import index from './components/index.vue'
import formElement from './components/formElement.vue'
// import HelloWorld from './components/HelloWorld.vue'
// import Home from './components/index.vue'

export default {
  name: 'App',
  components: {
    // HelloWorld
    index,
    formElement
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
