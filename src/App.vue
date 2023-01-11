<template>
  <navbar></navbar>
  <home></home>
</template>

<script>
import navbar from './components/navbar.vue';
import home from './components/home.vue';
export default {
  name: 'App',
  components: {
    navbar,
    home
  }
}
</script>

<style>
#app {
  font-family: Inter, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Oxygen, Ubuntu, Cantarell, "Fira Sans", "Droid Sans", "Helvetica Neue", sans-serif;
  background-color: #1a1a1a;
}
</style>
