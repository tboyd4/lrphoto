<template>
  <v-app-bar collapse-on-scroll>
    <v-container>
      <v-row>
        <v-col class="col-3">
          <h1 class="font-weight-light">Lindsey Renae</h1>
        </v-col>
        <v-spacer></v-spacer>
        <v-col class="col-3 offset-1">
          <nuxt-link to="/about" class="links"><v-btn class="font-weight-light">About</v-btn></nuxt-link>

          <nuxt-link to="/contact" class="links"><v-btn class="font-weight-light">Contact</v-btn></nuxt-link>
        </v-col>
      </v-row>
    </v-container>
  </v-app-bar>
</template>

<script>
    export default {
        
    }
</script>

<style  scoped>
  .links {
    text-decoration: none;
    font-size: 32px;
  }
</style>