<template>
  <div>
    <carousel>

      <carousel-slide>
        salut
      </carousel-slide>

      <carousel-slide>
        au revoir
      </carousel-slide>

    </carousel>
  </div>
</template>

<script>
import Carousel from './components/carousel/Carousel.vue'
import CarouselSlide from './components/carousel/CarouselSlide.vue'

export default {
  name: 'App',
  components: {
    Carousel,
    CarouselSlide
  },

  mounted () {
    console.log('toto')
  }
}
</script>
