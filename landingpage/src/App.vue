<template>
  <the-header></the-header>
  <theHero></theHero>
  <the-main></the-main>
  <the-footer></the-footer>
</template>

<script lang="ts">
import TheFooter from './components/TheFooter.vue';
import TheHeader from "./components/TheHeader.vue";
import TheHero from "./components/TheHero.vue";
import TheMain from "./components/TheMain.vue";

export default {
  name: "App",
  components: { TheHeader, TheHero, TheMain, TheFooter },
};
</script>

<style></style>
