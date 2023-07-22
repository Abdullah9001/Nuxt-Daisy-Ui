<template>
  <div class="bg-gray-100">
    <header class="px-14 justify-center flex py-8">
      <h1 class="text-white text-2xl text-gray-600 font-bold">About Us</h1>
    </header>
    <main class="container mx-auto my-8 px-4">
      <section class="bg-slate-600 p-8 rounded-lg shadow-md">
        <h2 class="text-2xl text-white font-bold mb-4">Our Story</h2>
        <p class="text-white">
          Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed sit amet
          tortor sed turpis varius bibendum. Fusce vel ligula vel felis laoreet
          tristique in vitae nunc. Vestibulum a pellentesque sapien. Mauris sit
          amet purus vel erat fringilla hendrerit.
        </p>
      </section>
      <section class="bg-slate-600 p-8 rounded-lg shadow-md mt-4">
        <h2 class="text-2xl text-white font-bold mb-4">Our Team</h2>
        <div class="grid grid-cols-3 gap-4">
          <div class="text-center">
            <img
              src="hero.jpg"
              alt="Team Member 1"
              class="w-24 h-24 mx-auto rounded-full"
            />
            <h3 class="text-lg text-white font-semibold mt-2">John Doe</h3>
            <p class="text-gray-100">Co-Founder</p>
          </div>
          <div class="text-center">
            <img
              src="hero-2.jpg"
              alt="Team Member 2"
              class="w-24 h-24 mx-auto rounded-full"
            />
            <h3 class="text-lg text-white font-semibold mt-2">Jane Smith</h3>
            <p class="text-gray-100">Co-Founder</p>
          </div>
          <div class="text-center">
            <img
              src="hero-3.jpg"
              alt="Team Member 3"
              class="w-24 h-24 mx-auto rounded-full"
            />
            <h3 class="text-lg text-white font-semibold mt-2">Bob Johnson</h3>
            <p class="text-gray-100">Lead Developer</p>
          </div>
        </div>
      </section>
    </main>
  </div>
</template>

<script setup></script>

<style lang="scss" scoped></style>
