<template>
    <v-flex sm4 pa-4 align-start justify-space-around row fill-height>
        <v-card>
          <!-- <v-card-title primary-title>
            <h3 class="headline mb-0">Game</h3>
          </v-card-title> -->
          <v-img
            src="img/ryse.jpeg"
          ></v-img>
          <v-card-text>
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Voluptas aspernatur modi incidunt exercitationem facilis doloribus excepturi hic provident vel nostrum. Sapiente accusamus distinctio labore, molestias porro consequatur eaque unde enim.
          </v-card-text>
          <v-card-actions>
            <v-btn color="info">
              <v-icon>
                info
              </v-icon>
              Info
            </v-btn>
            <v-btn color="success">
              <v-icon>
                shopping_cart
              </v-icon>
              Kopen
            </v-btn>
            <v-spacer></v-spacer>
            <div class="text-xs-center">
              <v-chip color="red" text-color="white">&euro; 19,95</v-chip>
            </div>
          </v-card-actions>
        </v-card>
      </v-flex>
</template>

<script>
export default {
    name: 'GameCard',
    props: [ 'game' ],
    data: () => ({}),
    created: () => {}
}
</script>

<style>

</style>
