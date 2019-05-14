<template>
  <v-container>
    <v-layout wrap>
      <GameCard v-for="game in games" 
        :key="game.id" 
        :game="game" />
    </v-layout>
  </v-container>
</template>

<script>
import GameCard from './GameCard'

  export default {
    name: 'Shop',
    components: {
      GameCard
    },
    data: () => ({ 
      games: [
        { id: 1, title: 'Ryse', description: 'This is a wider card with supporting text below as a natural lead-in to additional content. This content is a little bit longer.', image: 'img/ryse.jpeg', price: 19.95 },
        { id: 2, title: 'Amnesia', description: 'This is a wider card with supporting text below as a natural lead-in to additional content. This content is a little bit longer.', image: 'img/amnesia.jpeg', price: 29.95 },
        { id: 3, title: 'Avatar', description: 'This is a wider card with supporting text below as a natural lead-in to additional content. This content is a little bit longer.', image: 'img/avatar.jpeg', price: 39.95 },
        { id: 4, title: 'Horizon Zero Dawn', description: 'This is a wider card with supporting text below as a natural lead-in to additional content. This content is a little bit longer.', image: 'img/horizonzerodawn.jpeg', price: 39.95 },
        { id: 5, title: 'Just cause 2', description: 'This is a wider card with supporting text below as a natural lead-in to additional content. This content is a little bit longer.', image: 'img/justcause.jpeg', price: 49.95 },
        { id: 6, title: 'Project Cars', description: 'This is a wider card with supporting text below as a natural lead-in to additional content. This content is a little bit longer.', image: 'img/projectcars.jpeg', price: 29.95 },
        { id: 7, title: 'Prototype 2', description: 'This is a wider card with supporting text below as a natural lead-in to additional content. This content is a little bit longer.', image: 'img/prototype2.jpeg', price: 39.95 },
        { id: 8, title: 'Trine', description: 'This is a wider card with supporting text below as a natural lead-in to additional content. This content is a little bit longer.', image: 'img/trine.jpeg', price: 49.95 },
        { id: 9, title: 'Watch Dogs', description: 'This is a wider card with supporting text below as a natural lead-in to additional content. This content is a little bit longer.', image: 'img/watchdogs.jpeg', price: 19.95 }
      ]
     })
  }
</script>

<style>

</style>
