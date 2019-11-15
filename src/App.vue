<template>
  <div id="app">
    <img alt="Vue logo" src="https://pbs.twimg.com/profile_images/1161653602806575105/BiccqAlf_400x400.jpg" width="100px" height="100"   >
    <HelloWorld msg="" />
  </div>
</template>

<script>
import HelloWorld from "./components/home.vue";

export default {
  name: "app",
  components: {
    HelloWorld
  }
};
</script>



<style>
#app {
  font-family: "Avenir", Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #111; 
}

#para1{
  color:#111;
  margin-left: -1000px;
}
</style>
