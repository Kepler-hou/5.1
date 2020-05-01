<template>
  <div id="app">
    <Header></Header>
    <Nav></Nav>
    <mycenter></mycenter>
    <Footer></Footer>


  </div>
</template>

<script>
import Header from './components/common/Header.vue'
import Nav from './components/common/Nav.vue'
import mycenter from './components/main/mycenter/Mycenter.vue'
import Footer from './components/common/Footer.vue'

export default {
  name: 'App',
  components: {
    Header,
    Nav,
    mycenter,
    Footer
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  background-color: #f4f4f4;
  }
  li{
    list-style: none;
  }
  .clear{
    clear: both;
  }
  
</style>
