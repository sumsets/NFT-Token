<template>
  <div id="app">
    <!-- <img alt="Vue logo" src="./assets/logo.png"> -->
    <deneme-deneme msg="oguz metehan" :no="1453"/>
  </div>
</template>

<script>
import DenemeDeneme from './components/DenemeDeneme.vue';

export default {
  name: 'App',
  components: {
    DenemeDeneme,
  },
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
  width: 375px;
}
</style>
