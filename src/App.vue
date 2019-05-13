<template>
  <v-app>
    <v-toolbar app dark>
      <v-toolbar-title class="headline text-uppercase">
        <span>GameShop</span>        
      </v-toolbar-title>
      <v-spacer></v-spacer>
      <v-badge right>
        <template v-slot:badge>
          <span>6</span>
        </template>
        <v-icon
          large
          color="grey lighten-1"
        >
          shopping_cart
        </v-icon>
      </v-badge>
    </v-toolbar>

    <v-content>
      <Shop />
    </v-content>
  </v-app>
</template>

<script>
import Shop from './components/Shop'

export default {
  name: 'App',
  components: {
    Shop
  },
  data () {
    return {
      //
    }
  }
}
</script>
