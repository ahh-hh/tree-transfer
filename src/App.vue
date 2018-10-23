<template>
  <div id="app">
    <ElTreeTransferDemo />
  </div>
</template>

<script>
import ElTreeTransferDemo from './components/ElTreeTransferDemo.vue'

export default {
  name: 'app',
  components: {
    ElTreeTransferDemo
  }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
