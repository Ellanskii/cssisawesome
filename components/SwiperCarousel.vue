<template lang="pug">
.swiper-container
    .swiper-wrapper
        slot
    .swiper-pagination(v-if="pagination")
    template(v-if="navigation")
        .swiper-button-prev
        .swiper-button-next
    .swiper-scrollbar(v-if="scrollbar")

</template>

<script>
import Swiper from "swiper";
export default {
  props: {
    pagination: {
      type: Boolean,
      default: false
    },
    navigation: {
      type: Boolean,
      default: false
    },
    scrollbar: {
      type: Boolean,
      default: false
    }
  },
  mounted() {
    const selector = this.$el.id ? `#${this.$el.id}` : ".swiper-container";
    const swiperConfig = {};
    if (this.pagination) {
      swiperConfig.pagination = {
        el: ".swiper-pagination"
      };
    }
    if (this.navigation) {
      swiperConfig.navigation = {
        nextEl: ".swiper-button-next",
        prevEl: ".swiper-button-prev"
      };
    }
    if (this.scrollbar) {
      swiperConfig.scrollbar = {
        el: ".swiper-scrollbar"
      };
    }
    const swiper = new Swiper(selector, swiperConfig);
  }
};
</script>

<style lang="scss">
@import "node_modules/swiper/dist/css/swiper";

.swiper-pagination-bullet {
  &-active {
    background: linear-gradient(45deg, $violet, $purple, $orange);
    box-shadow: 0px 0px 8px 3px $violet;
  }
}
</style>
