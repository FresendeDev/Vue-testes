<template>
  <div class="container">
    <Youtube />
    <imag src="./src/assets/ondas.svg" />

    <Test2 />
    <imag src="./src/assets/casa.jpeg" height="100%" width="100%" />
  </div>
</template>

<script>
import Imag from "./components/imag.vue";
import Test2 from "./components/Test2.vue";
import Youtube from "./components/Youtube.vue";
export default {
  components: { Youtube, Imag, Test2 },
};
</script>

<style>
body {
  min-width: 230px;
}
</style>
