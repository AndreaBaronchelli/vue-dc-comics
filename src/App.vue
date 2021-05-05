<template>
  <div id="app">
    <!-- HEADER -->
    <Header />

    <!-- HERO -->
    <Hero />
    
    <!-- MAIN -->
    <Comics />

    <!-- BAR -->
    <Bar />

    <!-- FOOTER -->
    <Footer />
  </div>
</template>

<script>
import Header from '@/components/Header.vue'
import Hero from '@/components/Hero.vue'
import Comics from '@/components/Comics.vue'
import Bar from '@/components/Bar.vue'
import Footer from '@/components/Footer.vue'

export default {
  name: 'App',
  components: {
    Header,
    Hero,
    Comics,
    Bar,
    Footer,
  }
}
</script>

<style lang="scss">
@import "./styles/general.scss";
@import "./styles/utilities.scss";
@import "./styles/vars.scss";
</style>
