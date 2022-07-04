<template>
  <div id="app">
    
    <AppHeader />

    <AppMain />

  </div>
</template>

<script>

import AppHeader from "./components/appHeader.vue";
import AppMain from "./components/appMain.vue";



export default {
  name: 'App',
  components: {
    AppHeader,
    AppMain
}
}
</script>

<style>

*{
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body{
  background: #212d38;
}

#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #fff;
}
</style>
