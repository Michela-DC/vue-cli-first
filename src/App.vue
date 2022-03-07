<template>
  <div id="app">
    <!-- <img alt="Vue logo" src="./assets/logo.png"> -->
    <!-- <HelloWorld msg="Welcome to Your Vue.js App"/> -->
    <TitleVueCli/>
    <HeroJumbotron/>
  </div>
</template>

<script>
// import HelloWorld from './components/HelloWorld.vue'
import TitleVueCli from './components/TitleVueCli.vue'
import HeroJumbotron from './components/HeroJumbotron.vue'

export default {
  name: 'App',
  components: {
    // HelloWorld,
    TitleVueCli,
    HeroJumbotron
  }
}
</script>

<style lang="scss">
*{
  box-sizing: border-box;
  margin: 0;
  padding: 0;
}

#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  // margin-top: 60px;
  height: 100vh;
  width: 80%;
  margin: 0 auto;
  display: flex;
  flex-direction: column;
}
</style>
