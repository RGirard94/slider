<template>
  <div>
    Index : {{ index }}
    <slot></slot>
  </div>
</template>

<script>
  export default {
    name: 'CarouselSlide',
    data () {
      return {
        index: 0
      }
    }
  }
</script>
