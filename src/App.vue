<template>
  <div id="app">
    <Title />
    <Img />
  </div>
</template>

<script>
import Title from "./components/Title.vue";
import img from "./components/Hero.vue";

export default {
  name: "App",
  components: {
    Title,
    img,
  },
};
</script>

<style lang="scss">
#app {
  // font-family: Avenir, Helvetica, Arial, sans-serif;
  // -webkit-font-smoothing: antialiased;
  // -moz-osx-font-smoothing: grayscale;
  // text-align: center;
  // color: #2c3e50;
  // margin-top: 60px;
  
  
  //reset
  *{
    margin: 0;
    padding: 0;
    box-sizing: border-box;
  }
}
</style>
