<template></template>

<script>
import AOS from "aos";
export default {
  mounted() {
    AOS.init();
  }
};
</script>

<style lang='scss'>
@import "node_modules/aos/dist/aos";
</style>
