<template>
  <div id="app">
    <router-link to="/"></router-link>
    <router-link to="/dashboard"></router-link>

      <router-view/>

  </div>
</template>

<script>
// import Home from './views/Home.vue'
// import FormHandler from './views/FormHandler.vue'


// export default {
//   name: 'App',
//   components: {
//     Home,
//   }
// }
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
