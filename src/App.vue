<template>
  <div id="app">
   <draggable></draggable>
  </div>
</template>

<script>
import Draggable from './components/Draggable' 

export default {
  name: 'App',
  components: {
    Draggable
  }
}
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
