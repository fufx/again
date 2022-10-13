<template>
  <img alt="Vue logo" src="./assets/logo.png">
 
  <model11></model11>

  <model33></model33>
  <div class="fullcent"></div>
</template>

<script>

import model11 from './components/model1/model11.vue';

import model33 from './components/model3/model33.vue';


export default {
  name: 'App',
  components: {
 
    model11,
 
    model33
    
  }
}
</script>

<style>
#app {
  background-image: url(./assets/background/background.jpg);
  /* background-size: cover; */
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  /* color: #2c3e50; */
  position: absolute;
  top: 0;
  right: 0;
  left: 0;
  bottom: 0;
}
.fullcent{
  background-image: url(./assets/background/background-shadow.png);
  position: absolute;
  top: 0;
  right: 0;
  left: 0;
  bottom: 0;
}
</style>
