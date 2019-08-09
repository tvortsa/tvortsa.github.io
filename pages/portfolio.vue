<template lang="pug">
    // Start Hero Carousel
    section.hero.is-medium.has-carousel
        #carousel-demo.hero-carousel
            .item-1
            // Slide Content
            .item-2
            // Slide Content
            .item-3
            // Slide Content
        .hero-head
        .hero-body
        .hero-foot
    // End Hero Carousel
</template>

<script>
import 'bulma/css/bulma.css'
import bulmaCarousel from 'bulma-carousel';
const carousels = bulmaCarousel.attach('.carousel', options);

bulmaCarousel.attach("#carousel-demo", {
    slidesToScroll: 1,
    slidesToShow: 4
    })

export default {
    
methods: {
    bulmaCar(){
    bulmaCarousel.attach("#carousel-demo", {
    slidesToScroll: 1,
    slidesToShow: 4
    })}
}

}
// bulmaCar();

</script>
<style>
@import url(https://cdnjs.cloudflare.com/ajax/libs/bulma/0.7.4/css/bulma.min.css);
@import url(https://cdn.jsdelivr.net/npm/bulma-carousel@4.0.4/dist/css/bulma-carousel.min.css);

</style>
