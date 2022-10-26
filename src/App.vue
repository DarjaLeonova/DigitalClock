<template>
  <DigitalClock />
</template>

<script>
import DigitalClock from "./components/DigitalClock.vue";
export default {
  name: "App",
  components: {
    DigitalClock: DigitalClock,
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
