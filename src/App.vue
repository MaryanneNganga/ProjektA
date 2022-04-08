<template>
  <img alt="Vue logo" src="./assets/logo.png">
  
  <firstTry/>
</template>

<script>

import firstTry from './components/firstTry.vue';

export default {
  name: 'App',
  components: {
  
    firstTry
  }

}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
