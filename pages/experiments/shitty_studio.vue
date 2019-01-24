<template lang="pug">
main.has-background-dark
    .hero.is-fullheight.is-primary.is-bold#first-section
        .hero-body
            .container.is-fluid
                .columns.is-vcentered 
                    .column.is-5
                        h1.title.is-1 Ваш сайт не приносит прибыль?
                        p.subtitle.is-3 Нам ли не знать
                        .button.is-info.is-medium Пойти нахуй
                    .column.is-7
                        img(src="/img/shitty_studio/thinking.svg").thinking
    share-links
    section.section
        .container.is-fluid.title-block
            h1.title.is-2 Вы получите
            p.subtitle Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua    
        .container
            ul.columns.is-multiline
                li.column.is-6-tablet.is-4-widescreen(data-aos="zoom-in"): .box
                    h2.title.is-4 Уникальный дизайн
                    p.subtitle 
                        | Выбрать его можно 
                        <a href="" class="has-text-gradient has-text-weight-bold">здесь</a>                  
                li.column.is-6-tablet.is-4-widescreen(data-aos="zoom-in" data-aos-delay="100"): .box
                    #qr_user_behavior_seo
                        <svg width="175" height="175" fill="none" xmlns="http://www.w3.org/2000/svg"><defs><clipPath id="qr_user_behavior_seo_mask" clipPathUnits="objectBoundingBox"><path transform="scale(0.00571428571)" d="M7 0H0v7h7V0zM14 0H7v7h7V0zM21 0h-7v7h7V0zM28 0h-7v7h7V0zM35 0h-7v7h7V0zM42 0h-7v7h7V0zM49 0h-7v7h7V0zM63 0h-7v7h7V0zM84 0h-7v7h7V0zM91 0h-7v7h7V0zM98 0h-7v7h7V0zM119 0h-7v7h7V0zM133 0h-7v7h7V0zM140 0h-7v7h7V0zM147 0h-7v7h7V0zM154 0h-7v7h7V0zM161 0h-7v7h7V0zM168 0h-7v7h7V0zM175 0h-7v7h7V0zM7 7H0v7h7V7zM49 7h-7v7h7V7zM63 7h-7v7h7V7zM70 7h-7v7h7V7zM77 7h-7v7h7V7zM91 7h-7v7h7V7zM98 7h-7v7h7V7zM119 7h-7v7h7V7zM133 7h-7v7h7V7zM175 7h-7v7h7V7zM7 14H0v7h7v-7zM21 14h-7v7h7v-7zM28 14h-7v7h7v-7zM35 14h-7v7h7v-7zM49 14h-7v7h7v-7zM77 14h-7v7h7v-7zM84 14h-7v7h7v-7zM91 14h-7v7h7v-7zM98 14h-7v7h7v-7zM105 14h-7v7h7v-7zM133 14h-7v7h7v-7zM147 14h-7v7h7v-7zM154 14h-7v7h7v-7zM161 14h-7v7h7v-7zM175 14h-7v7h7v-7zM7 21H0v7h7v-7zM21 21h-7v7h7v-7zM28 21h-7v7h7v-7zM35 21h-7v7h7v-7zM49 21h-7v7h7v-7zM77 21h-7v7h7v-7zM105 21h-7v7h7v-7zM119 21h-7v7h7v-7zM133 21h-7v7h7v-7zM147 21h-7v7h7v-7zM154 21h-7v7h7v-7zM161 21h-7v7h7v-7zM175 21h-7v7h7v-7zM7 28H0v7h7v-7zM21 28h-7v7h7v-7zM28 28h-7v7h7v-7zM35 28h-7v7h7v-7zM49 28h-7v7h7v-7zM63 28h-7v7h7v-7zM70 28h-7v7h7v-7zM77 28h-7v7h7v-7zM84 28h-7v7h7v-7zM105 28h-7v7h7v-7zM119 28h-7v7h7v-7zM133 28h-7v7h7v-7zM147 28h-7v7h7v-7zM154 28h-7v7h7v-7zM161 28h-7v7h7v-7zM175 28h-7v7h7v-7zM7 35H0v7h7v-7zM49 35h-7v7h7v-7zM63 35h-7v7h7v-7zM84 35h-7v7h7v-7zM105 35h-7v7h7v-7zM133 35h-7v7h7v-7zM175 35h-7v7h7v-7zM7 42H0v7h7v-7zM14 42H7v7h7v-7zM21 42h-7v7h7v-7zM28 42h-7v7h7v-7zM35 42h-7v7h7v-7zM42 42h-7v7h7v-7zM49 42h-7v7h7v-7zM63 42h-7v7h7v-7zM77 42h-7v7h7v-7zM91 42h-7v7h7v-7zM105 42h-7v7h7v-7zM119 42h-7v7h7v-7zM133 42h-7v7h7v-7zM140 42h-7v7h7v-7zM147 42h-7v7h7v-7zM154 42h-7v7h7v-7zM161 42h-7v7h7v-7zM168 42h-7v7h7v-7zM175 42h-7v7h7v-7zM63 49h-7v7h7v-7zM77 49h-7v7h7v-7zM84 49h-7v7h7v-7zM91 49h-7v7h7v-7zM105 49h-7v7h7v-7zM119 49h-7v7h7v-7zM7 56H0v7h7v-7zM14 56H7v7h7v-7zM21 56h-7v7h7v-7zM42 56h-7v7h7v-7zM49 56h-7v7h7v-7zM63 56h-7v7h7v-7zM70 56h-7v7h7v-7zM77 56h-7v7h7v-7zM98 56h-7v7h7v-7zM112 56h-7v7h7v-7zM119 56h-7v7h7v-7zM126 56h-7v7h7v-7zM133 56h-7v7h7v-7zM140 56h-7v7h7v-7zM147 56h-7v7h7v-7zM168 56h-7v7h7v-7zM175 56h-7v7h7v-7zM7 63H0v7h7v-7zM14 63H7v7h7v-7zM28 63h-7v7h7v-7zM42 63h-7v7h7v-7zM56 63h-7v7h7v-7zM63 63h-7v7h7v-7zM70 63h-7v7h7v-7zM77 63h-7v7h7v-7zM98 63h-7v7h7v-7zM112 63h-7v7h7v-7zM119 63h-7v7h7v-7zM133 63h-7v7h7v-7zM140 63h-7v7h7v-7zM154 63h-7v7h7v-7zM168 63h-7v7h7v-7zM175 63h-7v7h7v-7zM21 70h-7v7h7v-7zM28 70h-7v7h7v-7zM35 70h-7v7h7v-7zM49 70h-7v7h7v-7zM56 70h-7v7h7v-7zM84 70h-7v7h7v-7zM98 70h-7v7h7v-7zM112 70h-7v7h7v-7zM154 70h-7v7h7v-7zM161 70h-7v7h7v-7zM175 70h-7v7h7v-7zM14 77H7v7h7v-7zM35 77h-7v7h7v-7zM63 77h-7v7h7v-7zM70 77h-7v7h7v-7zM112 77h-7v7h7v-7zM119 77h-7v7h7v-7zM126 77h-7v7h7v-7zM133 77h-7v7h7v-7zM140 77h-7v7h7v-7zM154 77h-7v7h7v-7zM14 84H7v7h7v-7zM21 84h-7v7h7v-7zM35 84h-7v7h7v-7zM49 84h-7v7h7v-7zM63 84h-7v7h7v-7zM70 84h-7v7h7v-7zM84 84h-7v7h7v-7zM91 84h-7v7h7v-7zM98 84h-7v7h7v-7zM119 84h-7v7h7v-7zM133 84h-7v7h7v-7zM140 84h-7v7h7v-7zM175 84h-7v7h7v-7zM35 91h-7v7h7v-7zM56 91h-7v7h7v-7zM70 91h-7v7h7v-7zM91 91h-7v7h7v-7zM105 91h-7v7h7v-7zM112 91h-7v7h7v-7zM133 91h-7v7h7v-7zM140 91h-7v7h7v-7zM168 91h-7v7h7v-7zM175 91h-7v7h7v-7zM7 98H0v7h7v-7zM14 98H7v7h7v-7zM35 98h-7v7h7v-7zM42 98h-7v7h7v-7zM49 98h-7v7h7v-7zM91 98h-7v7h7v-7zM105 98h-7v7h7v-7zM112 98h-7v7h7v-7zM119 98h-7v7h7v-7zM154 98h-7v7h7v-7zM161 98h-7v7h7v-7zM175 98h-7v7h7v-7zM21 105h-7v7h7v-7zM28 105h-7v7h7v-7zM42 105h-7v7h7v-7zM56 105h-7v7h7v-7zM77 105h-7v7h7v-7zM84 105h-7v7h7v-7zM91 105h-7v7h7v-7zM119 105h-7v7h7v-7zM126 105h-7v7h7v-7zM133 105h-7v7h7v-7zM140 105h-7v7h7v-7zM147 105h-7v7h7v-7zM154 105h-7v7h7v-7zM7 112H0v7h7v-7zM14 112H7v7h7v-7zM21 112h-7v7h7v-7zM28 112h-7v7h7v-7zM49 112h-7v7h7v-7zM56 112h-7v7h7v-7zM63 112h-7v7h7v-7zM70 112h-7v7h7v-7zM98 112h-7v7h7v-7zM105 112h-7v7h7v-7zM119 112h-7v7h7v-7zM126 112h-7v7h7v-7zM133 112h-7v7h7v-7zM140 112h-7v7h7v-7zM147 112h-7v7h7v-7zM168 112h-7v7h7v-7zM63 119h-7v7h7v-7zM70 119h-7v7h7v-7zM77 119h-7v7h7v-7zM98 119h-7v7h7v-7zM119 119h-7v7h7v-7zM147 119h-7v7h7v-7zM175 119h-7v7h7v-7zM7 126H0v7h7v-7zM14 126H7v7h7v-7zM21 126h-7v7h7v-7zM28 126h-7v7h7v-7zM35 126h-7v7h7v-7zM42 126h-7v7h7v-7zM49 126h-7v7h7v-7zM77 126h-7v7h7v-7zM84 126h-7v7h7v-7zM119 126h-7v7h7v-7zM133 126h-7v7h7v-7zM147 126h-7v7h7v-7zM175 126h-7v7h7v-7zM7 133H0v7h7v-7zM49 133h-7v7h7v-7zM63 133h-7v7h7v-7zM98 133h-7v7h7v-7zM112 133h-7v7h7v-7zM119 133h-7v7h7v-7zM147 133h-7v7h7v-7zM168 133h-7v7h7v-7zM7 140H0v7h7v-7zM21 140h-7v7h7v-7zM28 140h-7v7h7v-7zM35 140h-7v7h7v-7zM49 140h-7v7h7v-7zM70 140h-7v7h7v-7zM84 140h-7v7h7v-7zM91 140h-7v7h7v-7zM98 140h-7v7h7v-7zM112 140h-7v7h7v-7zM119 140h-7v7h7v-7zM126 140h-7v7h7v-7zM133 140h-7v7h7v-7zM140 140h-7v7h7v-7zM147 140h-7v7h7v-7zM175 140h-7v7h7v-7zM7 147H0v7h7v-7zM21 147h-7v7h7v-7zM28 147h-7v7h7v-7zM35 147h-7v7h7v-7zM49 147h-7v7h7v-7zM91 147h-7v7h7v-7zM112 147h-7v7h7v-7zM119 147h-7v7h7v-7zM147 147h-7v7h7v-7zM161 147h-7v7h7v-7zM168 147h-7v7h7v-7zM7 154H0v7h7v-7zM21 154h-7v7h7v-7zM28 154h-7v7h7v-7zM35 154h-7v7h7v-7zM49 154h-7v7h7v-7zM63 154h-7v7h7v-7zM70 154h-7v7h7v-7zM77 154h-7v7h7v-7zM91 154h-7v7h7v-7zM98 154h-7v7h7v-7zM105 154h-7v7h7v-7zM119 154h-7v7h7v-7zM126 154h-7v7h7v-7zM140 154h-7v7h7v-7zM147 154h-7v7h7v-7zM154 154h-7v7h7v-7zM168 154h-7v7h7v-7zM175 154h-7v7h7v-7zM7 161H0v7h7v-7zM49 161h-7v7h7v-7zM63 161h-7v7h7v-7zM70 161h-7v7h7v-7zM84 161h-7v7h7v-7zM91 161h-7v7h7v-7zM105 161h-7v7h7v-7zM119 161h-7v7h7v-7zM126 161h-7v7h7v-7zM133 161h-7v7h7v-7zM140 161h-7v7h7v-7zM147 161h-7v7h7v-7zM7 168H0v7h7v-7zM14 168H7v7h7v-7zM21 168h-7v7h7v-7zM28 168h-7v7h7v-7zM35 168h-7v7h7v-7zM42 168h-7v7h7v-7zM49 168h-7v7h7v-7zM63 168h-7v7h7v-7zM70 168h-7v7h7v-7zM77 168h-7v7h7v-7zM98 168h-7v7h7v-7zM105 168h-7v7h7v-7zM119 168h-7v7h7v-7zM126 168h-7v7h7v-7zM154 168h-7v7h7v-7zM175 168h-7v7h7v-7z" fill="#000"/></clipPath></defs></svg>
                    h2.title.is-4 Продуманный UX
                    p.subtitle Отсканируйте QR-код, чтобы узнать больше
                li.column.is-6-tablet.is-4-widescreen(data-aos="zoom-in" data-aos-delay="200"): .box.has-background-test
                    h2.title.is-4 Отличные поведенческие факторы
                    p.subtitle Время, проведённое на сайте, влияет на его позиции в поисковой выдаче
                    escaping-button
                li.column.is-6-tablet.is-4-widescreen(data-aos="zoom-in" data-aos-delay="300"): .box
                    h2.title.is-4 Кратчайшие сроки
                    p.subtitle Выйдет как выйдет, так зачем ждать?  
                li.column.is-6-tablet.is-4-widescreen(data-aos="zoom-in" data-aos-delay="400"): .box
                    h2.title.is-4 Оригинальный контент
                    p.subtitle Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua                        
                li.column.is-6-tablet.is-4-widescreen(data-aos="zoom-in" data-aos-delay="500"): .box
                    h2.title.is-4 Поддержка и обслуживание
                    p.subtitle 
                        | Всего за 3000&nbsp;₽ в месяц мы размесим Ваш сайт с кучей других на 
                        <a href="" class="has-text-gradient has-text-weight-bold">самом дешёвом хостинге</a>    
    section.section
        h1.title.is-2 Наша команда
        p.subtitle Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua       
        swiper-carousel#team(pagination scrollbar navigation)
            .swiper-slide
                h2.title.is-4 Дизайнер-натурал
                p Тем не менее, дело своё знает
            .swiper-slide
                h2.title.is-4 Копирайтер
                p Наш лучше ихнего
            .swiper-slide
                h2.title.is-4 Сеошник
                p Родители нашли его в ТОП-10
            .swiper-slide
                h2.title.is-4 Антон
                p Гандон                
            .swiper-slide
                h2.title.is-4 Пиарщик
                p Напиздил про дизайнера 
    //- animations-on-scroll
    //- .pixel
    

</template>

<script>
import EscapingButton from "@/components/shitty_studio/EscapingButton";
import SwiperCarousel from "@/components/SwiperCarousel";
import ShareLinks from "@/components/ShareLinks";
// import AnimationsOnScroll from "@/components/AnimationsOnScroll";

export default {
  components: {
    EscapingButton,
    SwiperCarousel,
    ShareLinks
    // AnimationsOnScroll
  }
};
</script>

<style lang="scss">
#first-section {
    background: url(/img/shitty_studio/hero_bg.svg) no-repeat top right;
    background-size: 60% 90%;

    .thinking {
        max-height: 80vh;
    }
}
#qr_user_behavior_seo {
    width: 100px;
    height: 100px;
    margin-bottom: 1rem;
    background: linear-gradient(45deg, $violet, $purple, $orange);
    clip-path: url(#qr_user_behavior_seo_mask);
}
.box {
    background-color: rgba(#252733, 0.9);
    // background-image: linear-gradient(to top, rgba($violet, 0.5), rgba($purple, 0.1));
    // background-attachment: fixed;
    min-height: 100%;
}
.pixel {
    width: 1px;
    height: 1px;
    background: cyan;
    position: fixed;
    top: 200px;
    left: 150px;
}
.has-background-dark {
    background-size: cover;
    background-image: url(/img/shitty_studio/Group.svg);
    // background-attachment: fixed;
}
.title-block {
    margin-bottom: 2rem;
    .title, .subtitle {
        max-width: 600px;
    }
}
</style>
