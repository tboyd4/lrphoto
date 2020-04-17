<template>
  <v-card class="overflow-hidden">
    <v-app-bar
      absolute
      color="white"
      flat
      light
      hide-on-scroll
      prominent
      scroll-target="#scrolling-techniques-4"
    >
      <v-toolbar-title class="display-3 title-text" >Lindsey Renae Photography</v-toolbar-title>

      <v-spacer></v-spacer>

      <v-btn depressed class="mx-2 my-1 white">
        <nuxt-link class="links black--text" to="/about">About</nuxt-link>
      </v-btn>

      <v-btn depressed class="mx-2 my-1 white">
        <nuxt-link class="links black--text" to="/contact">Contact</nuxt-link>
      </v-btn>

    </v-app-bar>
    <v-sheet id="scrolling-techniques-4" class="overflow-y-auto" max-height="600">
      <v-container style="height: 1000px;"></v-container>
    </v-sheet>
  </v-card>
</template>

<script>
export default {}
</script>

<style  scoped>
.links {
  text-decoration: none;
  font-size: 24px;
}
.title-text {
  font-size: 34px;
}
</style>