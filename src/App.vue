<template>
   <h1 class="text-center">{{ tittle }}</h1>
   <Calculator />
</template>

<script>
import Calculator from "./components/Calculator.vue";

export default {
   name: "App",
   components: {
      Calculator,
   },
   data() {
      return {
         tittle: "Test Calculator VueJs",
      };
   },
};
</script>

<style>
body {
   background-color: #19c88d;
}
</style>
