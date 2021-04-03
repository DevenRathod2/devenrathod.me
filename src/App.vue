<template>
  <div id="app">
    <HelloWorld/>
  </div>
</template>

<script>
import HelloWorld from "./components/Home/Home.vue";


export default {
  name: "App",
  components: {
    HelloWorld,
  },
};
</script>


<style>
@import url('https://fonts.googleapis.com/css2?family=Poppins&display=swap');
#app {
  font-family: 'Poppins', sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  margin-top: 60px;
}
</style>
