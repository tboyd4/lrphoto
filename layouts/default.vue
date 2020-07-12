<template>
  <v-app class="white">
    <head-bar></head-bar>
    <v-content>
      <nuxt></nuxt>
    </v-content>
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
