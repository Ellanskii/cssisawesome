<template lang="pug">
    .escaping-button-container(@mouseover.passive="escape" :style="style")
        nuxt-link.button(to="/") {{ currentText }}
</template>

<script>
export default {
  data() {
    return {
      initialText: "Как?",
      insults: ["Ну как же?", "Не понимаю", "Памагите!", "Что происходит?"],
      currentText: "Как?",
      style: {
        transform: "translate(0, 0)"
      }
    };
  },
  methods: {
    escape(e) {
      const rect = this.$el.getBoundingClientRect();
      const centerX = rect.left + rect.width / 2
      const centerY = rect.top + rect.height / 2
      const escapingDistanceX = (centerX - e.pageX) * 3
      const escapingDistanceY = (centerY - e.pageY) * 3

      this.style.transform = `translate(${escapingDistanceX}px, ${escapingDistanceY}px)`;
    //   this.currentText = this.insults[
    //     Math.floor(Math.random() * this.insults.length)
    //   ];
      setTimeout(this.reset, 2000);
    },
    reset() {
      this.style.transform = "translate(0, 0)";
      this.currentText = this.initialText;
    }
  }
};
</script>

<style lang="scss" scoped>
.escaping-button-container {
  display: inline-block;
  padding: 0.5rem;
  transition: transform 0.2s;
  position: absolute;
}
</style>
