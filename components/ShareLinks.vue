<template lang="pug">
.share-links(v-if="isClient")
    a.button.is-warning(
        v-if="socials.indexOf('vk') >= 0"
        :href="'https://vk.com/share.php?url=' + pageUrl" 
        target="_blank" 
        rel="nofollow" 
        title="Поделиться в ВК"
    )
        b-icon(icon="vk")
    a.button.is-warning(
        v-if="socials.indexOf('fb') >= 0"
        :href="'https://www.facebook.com/sharer/sharer.php?u=' + pageUrl" 
        target="_blank" 
        rel="nofollow" 
        title="Поделиться в Facebook"
    )
        b-icon(icon="facebook")    
    a.button.is-warning(
        v-if="socials.indexOf('twitter') >= 0"
        :href="'https://twitter.com/intent/tweet?url=' + pageUrl" 
        target="_blank" 
        rel="nofollow" 
        title="Поделиться в Twitter"
    )
        b-icon(icon="twitter")
</template>

<script>
export default {
  props: {
    socials: {
      type: Array,
      default: () => ["vk", "fb", "twitter"]
    }
  },
  data() {
    return {
      isClient: false,
      pageUrl: ""
    };
  },
  mounted() {
    this.isClient = true;
    this.pageUrl = window.location.href;
  }
};
</script>

<style lang="scss">
.share-links {
  .button {
    margin: 0.5rem;
  }
  @media screen and (min-width: 1088px) {
    position: sticky;
    top: 200px;
    width: 3.25rem;
    z-index: 2;
    height: 0px;
    overflow: visible;
  }
}
</style>
