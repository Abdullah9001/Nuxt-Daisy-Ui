<!-- pages/product.vue -->
<template>
  <div class="flex justify-center items-center container mx-auto h-screen">
    <div class="grid grid-cols-2 gap-4">
      <div class="col-span-1">
        <img
          :src="product.imageUrl"
          :alt="product.name"
          class="w-full rounded-lg"
        />
      </div>
      <div class="col-span-1">
        <h1 class="text-2xl font-bold mb-4">{{ product.name }}</h1>
        <p class="text-gray-600 mb-4">{{ product.description }}</p>
        <p class="text-xl font-semibold mb-2">${{ product.price }}</p>
        <button class="bg-blue-500 text-white px-4 py-2 rounded-lg">
          Add to Cart
        </button>
      </div>
    </div>
  </div>
</template>

<script setup>
const product = ref({
  name: "Product Name",
  description: "Product description goes here.",
  price: 99.99,
  imageUrl: "/card.jpg",
});
</script>
