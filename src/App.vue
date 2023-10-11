<script>

import Heaader from './components/Heaader.vue';
import Main from './components/Main.vue';
import Footer from './components/Footer.vue';

export default {
  name: 'App',
  components: {
    Heaader,
    Main,
    Footer,
}
}
</script>


<template>
  
  <Heaader />
  <Main />
  <Footer />

</template>



<style lang="scss">

@import 'bootstrap/scss/bootstrap';
@use './scss/main.scss';

</style>