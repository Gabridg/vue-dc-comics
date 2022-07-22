<template>
  <div id="app">
    <Header></Header>
  </div>
</template>

<script>
import Header from "./components/HeaderComponent.vue";

export default {
  name: 'App',
  components: {
    Header,
  }
}
</script>

<style lang="scss">
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

#app {
  font-family: "Segoe UI", "Open Sans", Helvetica, sans-serif;

}
</style>
