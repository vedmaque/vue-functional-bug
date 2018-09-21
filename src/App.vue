<template>
  <div id="app">
    <fun1 />
    <hr>
    <fun2 />
    <hr>
    <hr>
    <fun-template1 />
    <hr>
    <fun-template2 />
  </div>
</template>

<script>
import Fun1 from './components/Fun1.vue'
import Fun2 from './components/Fun2.vue'
import FunTemplate1 from './components/FunTemplate1.vue'
import FunTemplate2 from './components/FunTemplate2.vue'

export default {
  name: 'app',
  components: {
    Fun1,
    Fun2,
    FunTemplate1,
    FunTemplate2
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
