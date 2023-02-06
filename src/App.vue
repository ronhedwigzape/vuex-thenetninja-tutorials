<script setup>

</script>

<template>
  <div id="app">
    <product-list-one></product-list-one>
    <product-list-two></product-list-two>
  </div>
</template>
<script>
import ProductListOne from "./components/ProductListOne.vue";
import ProductListTwo from "./components/ProductListTwo.vue";

export default {
  components: {
    'product-list-one': ProductListOne,
    'product-list-two': ProductListTwo
  },
  data() {
    return {

    }
  }
}
</script>
<style scoped>
body {
  font-family: Ubuntu;
  color: #555;
}
/*nav a.router-link-exact-active {*/
/*  color: var(--color-text);*/
/*}*/

/*nav a.router-link-exact-active:hover {*/
/*  background-color: transparent;*/
/*}*/

</style>
