<template>
  <navbar></navbar>
  <boDy></boDy>
</template>

<script>
  import navbar from './components/navbar.vue';
  import boDy from './components/body.vue';
  export default {
    name: 'App',
    components: {
      navbar,
      boDy
    }
}
</script>

<style>
  #app {
    font-family: Inter, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Oxygen, Ubuntu, Cantarell, "Fira Sans", "Droid Sans", "Helvetica Neue", sans-serif;
  }
  @import './assets/css/base.css';
  @import './assets/css/buttons.css';
</style>
