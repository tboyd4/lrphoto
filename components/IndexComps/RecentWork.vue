<template>
  <div>
    <v-container>
      <v-row justify="center" align-content="center">
        <v-col class="col-md-3 text-center font-italic title">Recent Work</v-col>
      </v-row>
      <v-row>
        <v-col cols="12" sm="12" >
          <v-card>
            <v-container fluid>
              <v-row>
                <v-col v-for="pic in recents" :key="pic" class="d-flex child-flex" cols="4">
                  <v-card flat tile class="d-flex">
                    <v-img
                      :src="pic"
                      :lazy-src="`https://picsum.photos/10/6?image=${n * 5 + 10}`"
                      aspect-ratio="1"
                      class="grey lighten-2"
                    >
                      <template v-slot:placeholder>
                        <v-row class="fill-height ma-0" align="center" justify="center">
                          <v-progress-circular indeterminate color="grey lighten-5"></v-progress-circular>
                        </v-row>
                      </template>
                    </v-img>
                  </v-card>
                </v-col>
              </v-row>
            </v-container>
          </v-card>
        </v-col>
      </v-row>
    </v-container>
  </div>
</template>

<script>
export default {
  data() {
    return {
      recents: [
        "/recent_work/Devon.jpg",
        "/recent_work/fame.jpg",
        "/recent_work/Makayla1.jpg",
        "/recent_work/Patrick1.jpg",
        "/recent_work/stickflip.jpg",
        "/recent_work/Vivian2.jpg"
      ]
    }
  }
}
</script>

<style scoped>
</style>