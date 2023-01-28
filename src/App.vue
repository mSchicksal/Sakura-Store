<template>
  <navbar></navbar>
  <boDy></boDy>
  <fooTer></fooTer>

</template>

<script>
  import navbar from  './components/base/navbar.vue';
  import boDy from    './components/base/body.vue';
  import fooTer from  './components/base/footer.vue';

  export default {
    name: 'App',
    components: {
      navbar,
      boDy,
      fooTer
    }
}
</script>

<style>
  #app {
    font-family: Inter, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Oxygen, Ubuntu, Cantarell, "Fira Sans", "Droid Sans", "Helvetica Neue", sans-serif;
  }
  @import './assets/css/base.css';
  @import './assets/css/buttons.css';
  @import './assets/css/cards.css';
</style>
