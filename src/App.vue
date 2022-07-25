<template>
  <div id="app">
    <div class="container">
      <Header></Header>
    </div>
    <Main></Main>
    <Section></Section>
    <Footer></Footer>
  </div>
</template>

<script>
import Header from "./components/HeaderComponent.vue";
import Main from "./components/ContentMain.vue";
import TopFooter from "./components/TopFooter.vue";
import BottomFooter from "./components/BottomFooter.vue";

export default {
  name: 'App',
  components: {
    Header,
    Main,
    Section: TopFooter,
    Footer: BottomFooter,
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

  ul li a {
    text-decoration: none;
    color: #666;
  }

  ul {
    list-style-type: none;
  }

}
</style>
