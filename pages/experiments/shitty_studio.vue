<template lang="pug">
    section.hero
        .hero-head
            h1.title.has-text-centered Вы получите
        .hero-body
            .container
                ul.columns.is-multiline.is-mobile
                    li.column
                        h2.title.is-4 Уникальный дизайн
                        p.subtitle 
                            | Выбрать его можно 
                            <a href="">здесь</a>                  
                    li.column
                        h2.title.is-4 Продуманный UX
                        p.subtitle Отсканируйте QR-код, чтобы узнать больше
                    li.column
                        h2.title.is-4 Отличные поведенческие факторы
                        p.subtitle Время, проведённое на сайте, влияет на его позиции в поисковой выдаче
                        escaping-button
                    li.column
                        h2.title.is-4 Кратчайшие сроки
                        p.subtitle Выйдет как выйдет, так чего ждать?   
                    li.column
                        h2.title.is-4 Поддержка и обслуживание
                        p.subtitle 
                            | Всего за 3000&nbsp;₽ в месяц мы размесим Ваш сайт с кучей других на 
                            <a href="">самом дешёвом хостинге</a>                                     
</template>

<script>
import EscapingButton from '@/components/shitty_studio/EscapingButton'
export default {
    components: {
        EscapingButton
    }

}
</script>

<style lang="scss">

</style>
