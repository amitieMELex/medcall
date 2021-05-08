<template>
<div>
  <HelloWorld msg="Welcome to Your Vue.js App"/>
 
  <router-view/>
  <Footer/>
  
  </div>
  
  
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import Footer from './components/Footer.vue'


export default {
  name: 'App',
  components: {
    HelloWorld,
    Footer
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  
  margin-top: 0px;

}
</style>
