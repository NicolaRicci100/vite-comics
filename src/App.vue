<script>
import AppHeader from './components/AppHeader.vue';
import AppMain from './components/AppMain.vue';
import AppFooter from './components/AppFooter.vue';
export default {
  name: 'vite-comics',
  components: { AppHeader, AppMain, AppFooter },
  data() {
    return {}
  }
}
</script>

<template>
  <AppHeader />
  <AppMain />
  <AppFooter />
</template>

<style>
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  font-family: 'Open Sans', sans-serif;
}

/* immagine fluida */
img {
  max-width: 100%;
  height: auto;
}

.container {
  margin: 0 auto;
  max-width: 1200px;
}

ul {
  list-style-type: none;
}
</style>