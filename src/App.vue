<template>
  <div id="app">
    <img v-bind:alt="name" v-bind:src="imgPath" />
    <h1>{{ name }}</h1>
  </div>
</template>

<script>
export default {
  name: "App",
  data() {
    return {
      name: "Bitcoin",
      imgPath: "../assest/bitcoin-btc-logo.png",
      changePercent: 10,
    };
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
