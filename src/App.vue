<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png" />
    <PugTest />
  </div>
</template>

<script>
import PugTest from './components/PugTest.vue';

export default {
  name: 'App',
  components: {
    PugTest
  }
};
</script>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
