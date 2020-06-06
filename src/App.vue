<template>
  <div id="app">
    <img alt="Colored With Cannabis logo" src="./assets/CWC Logo.svg" class="logo">
    <div class="container">
      <HelloWorld/>
      <!-- <Initiatives/> -->
    </div>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
// import Initiatives from './components/Initiatives.vue'

export default {
  name: 'App',
  components: {
    HelloWorld,
    // Initiatives
  }
}
</script>

<style>
html, body {
  background-color: black;
}
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  margin-top: 60px;
  display: flex;
  flex-direction: column;
  justify-content: center;
  margin-left: 40%;
}

.logo {
    width: 525px;
    height: auto;
    order: 1;
  }

.container {
  order: 2;
  display: flex;
  flex-direction: row;
  align-items: center;
}

@media only screen and (max-width: 600px) {

  #app {
    margin: 0 auto;
  }

  .logo {
    width: 325px;
    margin-left: 10%;
    height: auto;
    order: 1;
  }
}
</style>
