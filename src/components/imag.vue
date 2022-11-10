<template>
  <img :src="src" />
</template>

<script>
const altu = "500px";

export default {
  name: "imag",
  props: {
    src: String,
  },
};
</script>

<style scoped>
img {
  height: 100px;
  width: 100px;
}
</style>
