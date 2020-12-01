<template>
  <div id="app">
    <HelloWorld msg="Welcome to Your Vue.js App"/>
    <RenderComponent />
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import RenderComponent from './components/RenderComponent.vue'

export default {
  name: 'App',
  components: {
    HelloWorld,
    RenderComponent
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
