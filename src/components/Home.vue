<template>
<div>
  <v-carousel cycle show-arrows-on-hover>
    <v-carousel-item
      v-for="(color, i) in colors"
      :key="color"
    >
      <v-sheet
        :color="color"
        height="100%"
        tile
      >
        <v-row
          class="fill-height"
          align="center"
          justify="center"
        >
          <div class="display-3">Slide {{ i + 1 }}</div>
        </v-row>
      </v-sheet>
    </v-carousel-item>
  </v-carousel>

  <v-container class="grey lighten-5">
    <v-row no-gutters>
      <v-col
        v-for="n in 3"
        :key="n"
        cols="12"
        sm="4"
      >
        <v-card
    class="mx-auto mt-10"
    max-width="400"
  >
    <v-img
      class="white--text"
      height="200px"
      src="https://cdn.vuetifyjs.com/images/cards/docks.jpg"
    >
      <v-card-title class="align-end fill-height">Top 10 Australian beaches</v-card-title>
    </v-img>

    <v-card-text>
      <span>Number 10</span><br>
      <span class="text--primary">
        <span>Whitehaven Beach</span><br>
        <span>Whitsunday Island, Whitsunday Islands</span>
      </span>
    </v-card-text>

    <v-card-actions>
      <v-btn
        text
        color="orange"
      >
        Share
      </v-btn>
      <v-btn
        text
        color="orange"
      >
        Explore
      </v-btn>
    </v-card-actions>
  </v-card>
      </v-col>
    </v-row>
    <v-row no-gutters>
      <v-col
        v-for="n in 3"
        :key="n"
        cols="12"
        sm="4"
      >
        <v-card
    class="mx-auto mt-10"
    max-width="400"
  >
    <v-img
      class="white--text"
      height="200px"
      src="https://cdn.vuetifyjs.com/images/cards/docks.jpg"
    >
      <v-card-title class="align-end fill-height">Top 10 Australian beaches</v-card-title>
    </v-img>

    <v-card-text>
      <span>Number 10</span><br>
      <span class="text--primary">
        <span>Whitehaven Beach</span><br>
        <span>Whitsunday Island, Whitsunday Islands</span>
      </span>
    </v-card-text>

    <v-card-actions>
      <v-btn
        text
        color="orange"
      >
        Share
      </v-btn>
      <v-btn
        text
        color="orange"
      >
        Explore
      </v-btn>
    </v-card-actions>
  </v-card>
      </v-col>
    </v-row>
  </v-container>
 
  
</div>
</template>
<script>
export default {
    data () {
      return {
        colors: [
          'primary',
          'secondary',
          'yellow darken-2',
          'red',
          'orange',
        ],
      }
    },
}
</script>
<style scoped>

</style>