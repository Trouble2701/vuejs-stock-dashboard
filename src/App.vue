<template>
  <div>
    <BaseCard>
      <h1>Überschrift</h1>
      <p>Das ist ein Beispieltext in der Karte.</p>
    </BaseCard>
  </div>
  </template>

<script>
import BaseCard from './components/BaseCard.vue';
export default {
  name: 'App',
  components: {
   BaseCard
  }
}
</script>

<style>

body{
  margin: 0;
  padding: 100px;
  min-height: 100vh;
  background: radial-gradient(71.11% 100% at 50% 0%, #020204 14.6%, #011F35 100%);
}

#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
