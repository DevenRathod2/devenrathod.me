<template>
  <div id="app">
    <Home/>
    <particles-bg color="#45d1a2" num=30 type="cobweb" :canvas="{backgroundColor:'#2A2E35'}" :bg="true"/>
  </div>
</template>
<script>
import Home from "./components/Home/Home.vue";
import { ParticlesBg } from "particles-bg-vue";

export default {
  name: "App",
  components: {
    Home,
    ParticlesBg
  },
};
</script>


<style>
@import url('https://fonts.googleapis.com/css2?family=Josefin+Sans&family=Open+Sans&family=Poppins:wght@200&display=swap');
#app {
  font-family: 'Josefin Sans', sans-serif;
  font-family: 'Open Sans', sans-serif;
  font-family: 'Poppins', sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  margin-top: 60px;
}
</style>
