<template>
  <div>
    <Title />
  </div>
</template>

<script>

import Title from "./components/Title.vue"

export default {
  name: 'App',
  components: {
    Title
  }
}
</script>

<style lang="scss">
    h1{
      color: blue;
    }
</style>
