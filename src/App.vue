<template>
  <div id="app">
    <div class="container">
      <Header></Header>
    </div>
    <Jumbo></Jumbo>
    <Main></Main>
    <Section></Section>
    <Footer></Footer>
  </div>
</template>

<script>
import Header from "./components/HeaderComponent.vue";
import Jumbo from "./components/JumboMain.vue";
import TopFooter from "./components/TopFooter.vue";
import BottomFooter from "./components/BottomFooter.vue";
import Main from "./components/MainContent.vue"

export default {
  name: 'App',
  components: {
    Header,
    Jumbo,
    Section: TopFooter,
    Footer: BottomFooter,
    Main,
  },
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
