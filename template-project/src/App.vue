<template>
  <img alt="Vue logo" src="./assets/logo.png">
  <Wejscowka/>
  <MainPage/>
</template>

<script>
import Wejscowka from './components/Wejscowka.vue'
import MainPage form './components/MainPage.vue'

export default {
  name: 'App',
  components: {
    Wejscowka,
    MainPage
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
