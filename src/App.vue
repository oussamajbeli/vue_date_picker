<template>
  <div id="app">
     <CalendarWidget />
  </div>
</template>

<script>
import CalendarWidget from './components/CalendarWidget.vue';
export default {
  name: 'App',
  components: {
    CalendarWidget
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
}
</style>
