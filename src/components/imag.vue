<template>
  <img :src="src" />
</template>

<!-- <script>
const altu = "500px";

export default {
  name: "imag",
  props: {
    src: String,
  },
};
</script> -->

<script setup>
// const altu = "300px";
defineProps({
  height: {
    type: String,
    default: "100px",
  },
  width: {
    type: String,
    default: "200px",
  },
});
</script>

<style>
img {
  height: v-bind(height);
  width: v-bind(width);
}
</style>
