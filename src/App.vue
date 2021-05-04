<template>
  <div id="app">
    <!-- HEADER -->
    <Header />
    
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
import Comics from '@/components/Comics.vue'
import Bar from '@/components/Bar.vue'
import Footer from '@/components/Footer.vue'

export default {
  name: 'App',
  components: {
    Header,
    Comics,
    Bar,
    Footer,
  }
}
</script>

<style lang="scss">
// GENERAL
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  font-family: 'Roboto', sans-serif;
}

a {
  color: gray;
  text-decoration: none;
}

// UTILITIES
.container {
  max-width: 1270px;
  margin: 0 auto;
}
</style>
