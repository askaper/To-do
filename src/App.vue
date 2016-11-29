<template>
  <div id="app">
    <!-- <img src="./assets/logo.png"> -->
    <list></list>
  </div>
</template>

<script>
import List from './components/List'
import AddTask from './components/AddTask'

export default {
  name: 'app',
  components: {
    List,
    AddTask
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
