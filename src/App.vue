<template>
  <div id="app">
    <Banner1 />
    <Sample />
    <Footer1 />
    <Accord1 />
  </div>
</template>

<script>
import 'bootstrap/dist/css/bootstrap.css';

import Sample from './components/Body/Sample.vue';
import Banner1 from './components/Header/Banner1.vue';
import Footer1 from './components/Footer/Footer1.vue';
import Accord1 from './components/Content/Accord1.vue';

export default {
  name: 'App',
  components: {
    Sample,
    Banner1,
    Footer1,
    Accord1,
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
