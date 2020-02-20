
<template>
  <div>
    <headset></headset>
    <div id="con">
      <navigaTion></navigaTion>
      <conTent></conTent>
    </div>
  </div>
</template>

<script>
import headset from "./components/head.vue";
import navigaTion from "./components/Navigation.vue";
import conTent from "./components/content.vue";

export default {
  name: "App",
  components: {
    headset,
    navigaTion,
    conTent
  },
  data() {
    return {
      msg: "dwahdjwah"
    };
  }
};
</script>

<style>
div {
  background-color: rgb(152, 208, 253);
}
#con {
  height: 300px;
  clear: both;
}
#app {
  width: 900px;
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  background-color: rgb(91, 189, 245);
  margin-bottom: 200px;
}
</style>
