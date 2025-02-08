<template>
  <p>{{ product.name }}</p>
  <p>{{ product.price }}</p>
  <p>{{ product.length }}</p>
</template>

<script>
  export default {
    name: "ProductInfo",
    props: {
      product: Object
    }
  }
</script>