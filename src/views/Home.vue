<template>
  <b-container>
    <b-row align-v="center">
      <b-col md="3">
        <b-card title="Card Title">
          <img class="mb-2" src="https://picsum.photos/600/300/?image=25" />
          <b-card-text>
            Some quick example text to build on the card title and make up the
            bulk of the card's content.
          </b-card-text>

          <b-button variant="primary">Go somewhere</b-button>
        </b-card>
      </b-col>
    </b-row>
  </b-container>

  <v-card elevation="2" shaped tile></v-card>
</template>

<script>
// @ is an alias to /src

export default {
  name: "Home",
  components: {},
};
</script>
