<template>
  <div id="app">
    <!--img alt="Vue logo" src="./assets/logo.png"-->
    <Topo/>
    <Campo/>
  </div>
</template>

<script>
import Topo from './components/Topo.vue'
import Campo from './components/Campo.vue'
export default {
  name: 'App',
  components: {
    Topo,
    Campo
  }
}
</script>

<style>
  *{
    margin:0;
    padding:0;
  }
</style>
