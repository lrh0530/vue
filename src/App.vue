<template>
  <div id="app">
    <mynavbar></mynavbar>
    <img src="./assets/logo.png">
    <router-view></router-view>
  </div>
</template>

<script>
import mynavbar from './components/AppComponents/Navbar.vue'
export default {
  name: 'app',
  components: {
    mynavbar
  }
}
</script>

<style>
#app {
  font-family: 'Avenir',Helvetica,Arial,sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #42b983;
  margin-top: 0px;
}
</style>
