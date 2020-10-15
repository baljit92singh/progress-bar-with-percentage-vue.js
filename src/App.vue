<template>
  <div id="app">
    <!-- <img alt="Vue logo" src="./assets/logo.png" />
    <HelloWorld msg="Welcome to Your Vue.js App" /> -->
    <h4>Progress Bar</h4>
    <br />
    <b-progress :value="value1" :max="max1" show-progress animated></b-progress>
    <br />
    <b-progress :value="value2" :max="max2" show-progress animated></b-progress>
    <br />
    <b-progress :value="value3" :max="max3" show-progress animated></b-progress>
    <br />
    <b-progress :value="value4" :max="max4" show-progress animated></b-progress>
    <br />
    <b-progress :value="value5" :max="max5" show-progress animated></b-progress>
    <br />
    <h4>Spinner</h4>
    <br />
    <vue-ellipse-progress :progress="myProgress1" />
    <br />
    <vue-ellipse-progress :progress="myProgress2" />
    <br />
    <vue-ellipse-progress :progress="myProgress3" />
    <br />
    <vue-ellipse-progress :progress="myProgress4" />
    <br />
    <vue-ellipse-progress :progress="myProgress5" />
  </div>
</template>

<script>
// import HelloWorld from "./components/HelloWorld.vue";

export default {
  name: "App",
  components: {
    // HelloWorld,
  },
  data() {
    return {
      value1: 20,
      max1: 100,
      value2: 40,
      max2: 100,
      value3: 60,
      max3: 100,
      value4: 80,
      max4: 100,
      value5: 100,
      max5: 100,
      myProgress1: 20,
      myProgress2: 40,
      myProgress3: 60,
      myProgress4: 80,
      myProgress5: 100,
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
