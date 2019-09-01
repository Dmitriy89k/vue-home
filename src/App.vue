<template>
  <div id="app">
    <Header/>
    <Tours/>
    <Footer/>
  </div>
</template>

<script>
import Header from './components/Header.vue'
import Footer from './components/Footer.vue'
import Tours from './components/Tours.vue'


export default {
  name: 'app',
  components: {
    Header,
    Footer,
    Tours,
  }
}
</script>

<style>
img {
  height: 100px;
  width: 100px;
}
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
