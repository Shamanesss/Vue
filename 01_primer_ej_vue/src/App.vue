<template>
<NavBar />
  <img alt="Vue logo" id="cat" src="./assets/pexels-александар-цветановић-1440387.jpg">
  <HelloWorld msg="Welcome to the First Page in Vue"/>
  <PrimerComponente msg1="Este es mi primer Componente"/>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import PrimerComponente from './components/PrimerComponente.vue'
import NavBar from './components/NavBar'

export default {
  name: 'App',
  components: {
    HelloWorld,
    PrimerComponente,
    NavBar
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
  font-size:4rem;
   color: #42b983;
}
#cat{
  width:40rem;
  border-radius:5%;
}

</style>
