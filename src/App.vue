<template>
  <div id="app">
    <cinema-seat-choose></cinema-seat-choose>
  </div>
</template>

<script>
  import cinemaSeatChoose from './components/cinema-seat-choose.vue'
  export default {
    name: 'App',
    components:{
      cinemaSeatChoose
    }
  }
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #2c3e50;
  height:100%;
}
body,html{
  height:100%;
  min-width: 1000px;
}
</style>
