<template>
  <div id="app">
    <h1>Cryptocurrency Chart</h1>
    <p>[BTC] (JPY)</p>
    <TheMatrics></TheMatrics>
    <div>TODO: Chart</div>
    <h5>TECH PLAY ACADEMY</h5>
  </div>
</template>

<script>
import TheMatrics from './components/TheMatrics';
import TheChart from './components/TheChart';

export default {
  name: 'App',
  components: {
    TheMatrics,
    TheChart,
  },
};

</script>

<style scoped>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #2c3e50;
  margin-top: 60px;
  text-align: center;
}

.metrics-container {
  display: flex;
  justify-content: center;
}

.metric-container {
  background: #ccc;
  width: 120px;
  height: 50px;
  padding: 10px;
  margin: 10px;
}
</style>
