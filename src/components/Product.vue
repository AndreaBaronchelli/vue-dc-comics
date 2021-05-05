<template>
  <div class="product">
      <img :src="details.thumb" alt="">
      <div class="label">{{ details.series }}</div>
  </div>
</template>

<script>
export default {
    name: "Product",
    props: ["details"]
}
</script>

<style>
  .product {
    margin-right: 25px;
    margin-bottom: 50px;
    width: calc(100% / 6 - 25px);
    cursor: pointer;
  }
  
  .label {
    font-size: 14px;
    color: #fff;
    text-transform: uppercase;
  }
</style>