<template>
  <img :src="src" />
</template>

<script>
// const altu = "500px";

export default {
  name: "imag",
  props: {
    src: String,
    height: {
      type: String,
      default: "auto",
    },
    width: {
      type: String,
      default: "auto",
    },
  },
};
</script>

<!-- <script setup>
// const altu = "300px";
defineProps({
  height: {
    type: String,
    default: "auto",
  },
  width: {
    type: String,
    default: "auto",
  },
});
</script> -->

<style>
img {
  height: v-bind(height);
  width: v-bind(width);
}
</style>
