<template>
  <div id="app">
    <div class="container">
      <Header></Header>
    </div>
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

  .container {
    max-width: 1200px;
    margin: 0 auto;
  }

}
</style>
