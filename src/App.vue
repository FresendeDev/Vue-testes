<template>
  <div class="container">
    <Youtube />
    <imag />
  </div>
</template>

<script>
import Imag from "./components/imag.vue";
import Youtube from "./components/Youtube.vue";
export default {
  components: { Youtube, Imag },
};
</script>

<style>
body {
  min-width: 230px;
}
</style>
