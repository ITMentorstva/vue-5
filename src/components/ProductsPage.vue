
<template>
  <p>Hello world</p>
  <ProductDetails :productList="productList" />
</template>

<script>

  import ProductDetails from "@/components/ProductDetails.vue";

  export default {
    name: "ProductsPage",
    components: {ProductDetails},
    props: {
      productList: Array
    }
  }

</script>