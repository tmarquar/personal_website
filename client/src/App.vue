<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <HomePage msg="Welcome to Your Vue.js App"/>
    <PageFooter/>
  </div>
</template>

<script>
import HomePage from './components/HomePage.vue'
import PageFooter from './components/layout/PageFooter.vue'

export default {
  name: 'App',
  components: {
    HomePage,
    PageFooter
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
