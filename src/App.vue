<template>

  <ProductsPage :productList="productList" />

</template>

<script>

import ProductsPage from "@/components/ProductsPage.vue";

export default {
  name: 'App',
  components: {ProductsPage},
  data: () => ({
    productList: [
      {
        "name": "HTML Course",
        "price": 150,
        "length": "3 months"
      },
      {
        "name": "JavaScript Course",
        "price": 200,
        "length": "4 months"
      },
      {
        "name": "Python Bootcamp",
        "price": 300,
        "length": "6 months"
      },
      {
        "name": "Web Design Masterclass",
        "price": 180,
        "length": "3.5 months"
      },
      {
        "name": "ReactJS Training",
        "price": 250,
        "length": "5 months"
      }
    ],
  })
}
</script>
