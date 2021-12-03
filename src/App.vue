<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <!-- <HelloWorld msg="Welcome to Your Vue.js App"/> -->
    <Welcome info="hi vuejs"/>
    <h2>ll</h2>
  </div>
</template>

<script>
// import HelloWorld from './components/HelloWorld.vue'
import Welcome from './components/Welcome.vue'
export default {
  name: 'App',
  components: {
    // HelloWorld,
    Welcome
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
