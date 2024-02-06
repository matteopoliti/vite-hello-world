<script>
import AppTitle from './components/AppTitle.vue';
import AppHero from './components/AppHero.vue';


export default {
  components: {
    AppTitle,
    AppHero
  }
}
</script>

<template>
  <div class="container">
    <AppTitle />
    <AppHero />

  </div>
</template>

<style>
.container {
  width: 60%;
  margin: 0 auto;
  background-color: lightgray;
}
</style>
