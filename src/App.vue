<template>
  <z-canvas :views='$options.components'></z-canvas>
</template>
<script>
import home from './components/home.vue'
import weight from './components/weight.vue'
import height from './components/height.vue'
import result from './components/result.vue'

export default {
  components: {
    home,
    weight,
    height,
    result
  },
  mounted () {
    this.$zircle.setView('home')
  }
}
</script>
<style>
@import url('https://fonts.googleapis.com/css?family=Source+Sans+Pro:400,700');
@import url('https://use.fontawesome.com/releases/v5.1.0/css/all.css');

body {
  font-size: 90%;
}
</style>

