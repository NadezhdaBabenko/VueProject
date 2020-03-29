<template>
  <div id="app">
    <StartPage/>
    <Features/>
    <Works/>
    <Team/>
    <Clients/>
    <Download/>
    <Footer/>
    <Copyright/>


  </div>
</template>

<script>
import StartPage from './components/StartPage';
import Features from './components/Features';
import Works from './components/Works';
import Team from './components/Team';
import Clients from './components/Clients';
import Download from './components/Download';
import Footer from './components/Footer';
import Copyright from './components/Copyright';








export default {
  name: 'App',
  components: {
    StartPage,
    Features,
    Works,
    Team,
    Clients,
    Download,
    Footer,
    Copyright
  }
}
</script>

<style>
#app {
  font-family: Raleway, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #3b3e41;
}
</style>
