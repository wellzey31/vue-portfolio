<template>
  <div id="app">
    <Navbar/>
    <Profile/>
  </div>
</template>

<script>
import Navbar from './components/Navbar.vue';
import Profile from './components/Profile.vue';

export default {
  name: 'App',
  components: {
    Navbar,
    Profile,
  },
};
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
