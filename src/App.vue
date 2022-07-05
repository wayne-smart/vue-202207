<template>
  <img alt="swan logo" src="./assets/new-logo.png">
  <MyApp msg="It's The End Of The World As We Know It"/>
</template>

<script>
import MyApp from './components/MyApp.vue'

export default {
  name: 'App',
  components: {
    MyApp
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
  background-color: #01ff78;
}
</style>
