<template>
 <div id="app">
   <Heading/>
   <calculator/>
 </div>

</template>

<script>
import Heading from "./components/Heading.vue";
import Calculator from "./components/Calculator.vue";
export default {
  name: "App",
  components: {
    Heading,
    Calculator
  },
};
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #1471ce;
  margin-top: 30px;
}
</style>
