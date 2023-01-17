<template>
  <nav class="container relative mx-auto p-6">
    <div class="flex items-center justify-between">
      <!-- Logo -->
      <div class="pt-2">
        <img src="@/assets/img/logo.svg" alt="" />
      </div>
      <!-- Menu Items -->
      <div class="hidden space-x-6 md:flex">
        <a href="#" class="hover:text-gray-400">Pricing</a>
        <a href="#" class="hover:text-gray-400">Product</a>
        <a href="#" class="hover:text-gray-400">About us</a>
        <a href="#" class="hover:text-gray-400">Careers</a>
        <a href="#" class="hover:text-gray-400">Community</a>
      </div>
      <!-- Button -->
      <a
        href="#"
        class="baseline hidden rounded-full bg-orange-600 p-3 px-6 text-white hover:bg-red-400 md:block"
        >Get Started</a
      >
    </div>
  </nav>
</template>
