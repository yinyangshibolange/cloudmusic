<template>
  <div id="app">
    <!-- <img alt="Vue logo" src="./assets/logo.png"> -->
    <Header></Header>
  <div class="clearfix">
    <Left class="float-left"></Left>
    <Right class="float-left"></Right>
  </div>

    <Footer></Footer>
  </div>
</template>

<script>
import Header from './layout/Header'
import Left from './layout/content/Left'
import Right from './layout/content/Right'
import Footer from './layout/Footer'
export default {
  name: 'App',
  components: {
    Header, Left, Right, Footer
  }
}
</script>

<style>
/* @import url('src/style/index.sass'); */
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
}
</style>
