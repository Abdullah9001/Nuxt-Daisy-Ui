<template>
  <div class="navbar bg-slate-500 sticky px-10 top-0 left-0 right-0 z-50">
    <div class="flex-1 bg">
      <NuxtLink to="/" class="outline-none text-white normal-case text-4xl"
        >Aj Blog</NuxtLink
      >
    </div>
    <div class="flex-none">
      <NuxtLink to="/" class="btn btn-ghost text-xs text-gray-300">
        Home
      </NuxtLink>
      <NuxtLink to="/about" class="btn btn-ghost text-xs text-gray-300">
        About
      </NuxtLink>
    </div>
  </div>
</template>

<script setup></script>

<style lang="scss" scoped></style>
