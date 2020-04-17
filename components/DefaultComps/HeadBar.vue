<template>
  <v-card>
    <v-app-bar
      absolute
      color="white"
      flat
      light
    >
      <v-btn class="pb-1 home mx-2 white" icon>
        <nuxt-link to="/">
          <v-img height="55px" width="55px" src="/IMG_0570.jpg"></v-img>
        </nuxt-link>
      </v-btn>

      <v-spacer></v-spacer>

      <v-btn depressed class="mx-2 my-1 white">
        <nuxt-link class="links black--text headline" to="/about">About</nuxt-link>
      </v-btn>

      <v-btn depressed class="mx-2 my-1 white">
        <nuxt-link class="links black--text headline" to="/contact">Contact</nuxt-link>
      </v-btn>
    </v-app-bar>
    
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
.home {
  cursor: pointer;
}
</style>