<template>
  <div id="app">
    <StartPage/>
    <Features/>
    <Works/>
  </div>
</template>

<script>
import StartPage from './components/StartPage';
import Features from './components/Features';
import Works from './components/Works';




export default {
  name: 'App',
  components: {
    StartPage,
    Features,
    Works
  }
}
</script>

<style>
#app {
  font-family: Raleway, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #2c3e50;
}
</style>
