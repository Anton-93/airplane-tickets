<template>
  <div id="app">
    <Flights></Flights>
  </div>
</template>

<script>
    import Flights from './components/Flights.vue'

    export default {
      name: 'app',
      components: {
        Flights
      }
    }
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
