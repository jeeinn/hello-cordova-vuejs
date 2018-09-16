<template>
  <div id="app">
    <img src="./assets/cordova_bot.png">
    <img src="./assets/vue_logo.png">
    <router-view/>
  </div>
</template>

<script>
export default {
  name: 'App'
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
#app > img {
  width: 200px;
  height: 200px;
}
</style>
