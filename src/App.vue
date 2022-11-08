<template>
  <div class="container">
    <Youtube />
  </div>
</template>

<script>
import Youtube from "./components/Youtube.vue";
export default {
  components: { Youtube },
};
</script>

<style>
body {
  min-width: 230px;
}
</style>
