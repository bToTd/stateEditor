<template>
  <div id="app">
    <State/>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld';
import State from './components/gojs/State'

export default {
  name: 'App',
  components: {
    HelloWorld,
    State
  }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
