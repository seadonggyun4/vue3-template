<template>
  <div>
    <div class="logo"></div>
    <HelloWorld msg="Welcome to Your Vue.js App"/>
  </div>
</template>

<script>
import HelloWorld from '../components/HelloWorld.vue'

export default {
  name: 'App',
  components: {
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
  margin-top: 60px;
}


.logo{
  margin: 0 auto;
  width: 200px;
  height: 200px;
  background: url(../assets/logo.png);
  background-repeat: no-repeat;
  background-size: cover;
}
</style>
