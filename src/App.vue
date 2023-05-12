<template>
  <div id="app">
    <h1>IDShop</h1>
    <p class="animate_animated animate_fadeInRight">Lorem ipsum dolor sit.</p>
    <font-awesome-icon icon="shopping-cart"></font-awesome-icon>
    <Price :value="4.23" />
  </div>
</template>

<script>
import { FontAwesomeIcon } from "@fortawesome/vue-fontawesome";
import Price from "./components/Price.vue";

export default {
  name: "App",
  components: {
    FontAwesomeIcon,
    Price,
  },
};
</script>
