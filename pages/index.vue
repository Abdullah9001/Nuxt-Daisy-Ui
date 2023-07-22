<script setup>
const { data } = await useLazyFetch(
  "https://dummyjson.com/products?limit=10&skip=10&select=title,price"
);
</script>

<template>
  <div class="bg-gray-100">
    <Hero />
    <div
      class="card"
      v-for="{
        id,

        price,

        title,
      } in data.products"
      :key="id"
    >
      <Card :id="id" :price="price" :title="title" />
    </div>
  </div>
</template>
