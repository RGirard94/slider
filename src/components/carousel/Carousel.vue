<template>
  <div>
    <slot></slot>
  </div>
</template>

<script>
  export default {
    name: 'Carousel',
    data () {
      return {
        index: 0,
        slides: []
      }
    },
    beforeMount () {
      console.log('toto')
      this.slides = this.$children
      this.slides.forEach((slide, i) => {
        slide.index = i
      })
    }
  }
</script>
