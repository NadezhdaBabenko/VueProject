<template>
  <div id="app">
    <StartPage/>
    <Features/>
    <Works/>
    <Team/>
    <Clients/>
  </div>
</template>

<script>
import StartPage from './components/StartPage';
import Features from './components/Features';
import Works from './components/Works';
import Team from './components/Team';
import Clients from './components/Clients';





export default {
  name: 'App',
  components: {
    StartPage,
    Features,
    Works,
    Team,
    Clients
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
