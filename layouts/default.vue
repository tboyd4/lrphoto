<template>
  <v-app dark>
    <head-bar></head-bar>
    <nuxt></nuxt>
    <foot-bar></foot-bar>
  </v-app>
</template>

<script>
import FootBar from '../components/DefaultComps/FootBar.vue'
import HeadBar from '../components/DefaultComps/HeadBar.vue'
export default {
  components: {
    FootBar,
    HeadBar
  }
}
</script>
