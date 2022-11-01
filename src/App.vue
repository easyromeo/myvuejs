<template>
  <ProductList :product="products" />
</template>

<script>
import ProductList from './components/ProductList.vue';

export default {
  name: 'App',
  components: { ProductList },
};
</script>

<style lang="stylus">

</style>
