<template>
  <div id="app">
 <Shop shop-title="Smartphones" />
  </div>

</template>

<script>
  import Shop from './components/Shop.vue';


  export default {
    components: {
    Shop
}
  }
</script>

<style>
#nav {
  padding: 30px;

/* &.router-link-exact-active {
  color: green;
 }  */
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
