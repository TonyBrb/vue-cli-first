<template>
  <div>
    <Title />
    <Hero />
  </div>
</template>

<script>

import Title from "./components/Title.vue"
import Hero from "./components/Hero.vue"

export default {
  name: 'App',
  components: {
    Title,
    Hero
  }
}
</script>

<style lang="scss">
    body{
      background-color: black;
    }
    h1{
      text-align: center;
      font-family: 'Trebuchet MS', 'Lucida Sans Unicode', 'Lucida Grande', 'Lucida Sans', Arial, sans-serif;
      color: blue;
    }

    .jumbotron{
      width:60%;
      margin: 0 auto;
    }
</style>
