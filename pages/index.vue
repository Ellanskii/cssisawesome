<template lang="pug">
    .hero.is-bold.is-info.is-fullheight
        .container.hero-body
            h1.title.has-text-centered CSS is awesome
            nuxt-link(to="experiments/shitty_studio") Web Agency
            nuxt-link(:to="{name: 'experiments-cyrillic'}") Кириллический адрес
</template>

<script>
export default {

}
</script>

<style lang="scss">

</style>