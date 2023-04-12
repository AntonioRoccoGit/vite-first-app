<script>
import AppBanner from "./components/AppBanner.vue"

export default {
  components: {
    AppBanner
  },
  data() {
    return {
      title: "Ciao come stai?"
    }
  }
}
</script>

<template>
  <h1>Hello World with vite {{ title }}</h1>
  <AppBanner></AppBanner>
</template>

<style>
h1 {
  color: red;
}
</style>