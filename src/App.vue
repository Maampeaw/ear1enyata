<template>
  <div id="app">
  <Home />
  <BelowHero />
  <Section3 />
  <Section4 />
  <Section5 />
  <Footer />
  </div>
</template>

<script>
import Home from './components/Home.vue'
import BelowHero from './components/BelowHero.vue'
import Section3 from './components/Section3.vue'
import Section4 from './components/Section4.vue'
import Section5 from './components/Section5.vue'
import Footer from './components/Footer.vue'

export default {
  name: 'App',
  components: {
    Home,
    BelowHero,
    Section3,
    Section4,
    Section5,
    Footer
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  /* text-align: center; */
  color: #2c3e50;
  margin-top: 32px;
}
*{
  padding: 0;
  margin: 0;
  box-sizing: border-box;
}
</style>
