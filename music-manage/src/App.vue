<template>
  <div id="app">
    <SongAudio />
    <router-view></router-view>
  </div>
</template>

<script>
//import SongAudio from './components/SongAudio';
export default {
  name: 'App',
//  components: {
//    SongAudio
//  }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  
}
</style>
