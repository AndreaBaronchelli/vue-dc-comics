<template>
  <div id="app">
    <!-- HEADER -->
    <Header />
    <!-- MAIN -->
    <Comics />
  </div>
</template>

<script>
import Header from '@/components/Header.vue'
import Comics from '@/components/Comics.vue'

export default {
  name: 'App',
  components: {
    Header,
    Comics
  }
}
</script>

<style lang="scss">
// GENERAL
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  font-family: sans-serif;
}

a {
  color: #574e54;
}

// UTILITIES
.container {
  max-width: 1270px;
  margin: 0 auto;
}
</style>
