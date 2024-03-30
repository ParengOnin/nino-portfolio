<template>
  <NavigationOptions></NavigationOptions>
  <HelloWorld msg="Lance Javate"/>
</template>

<script>
import NavigationOptions from './components/NavigationOptions.vue'
import HelloWorld from './components/HelloWorld.vue'

export default {
  name: 'App',
  components: {
    NavigationOptions,
    HelloWorld
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
}

</style>
