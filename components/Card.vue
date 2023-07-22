<template>
  <div
    class="flex flex-wrap h-100 w-100 m-auto justify-center items-center p-20"
  >
    <div class="card card-compact w-96 bg-base-100 shadow-2xl m-5">
      <figure>
        <img src="/card.jpg" alt="Shoes" />
      </figure>
      <div class="card-body">
        <h2 class="card-title">{{ title }}</h2>
        <p>If a dog chews shoes whose shoes does he choose?</p>
        <div class="card-actions">
          <NuxtLink :to="'/post/' + post.id" class="btn btn-info text-xs"
            >Buy Now</NuxtLink
          >
        </div>
      </div>
    </div>
  </div>
</template>

<script setup>
defineProps(["id", "price", "title"]);
</script>
