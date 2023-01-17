<template>
  <nav class="relative container mx-auto p-6">
    <div class="flex items-center justify-between">
      <!-- Logo -->
      <div class="pt-2">
        <img src="@/assets/img/logo.svg" alt="" />
      </div>
      <!-- Menu Items -->
      <div class="hidden md:flex space-x-6">
        <a href="#" class="hover:text-gray-400">Pricing</a>
        <a href="#" class="hover:text-gray-400">Product</a>
        <a href="#" class="hover:text-gray-400">About us</a>
        <a href="#" class="hover:text-gray-400">Careers</a>
        <a href="#" class="hover:text-gray-400">Community</a>
      </div>
      <!-- Button -->
      <a
        href="#"
        class="hidden md:block p-3 px-6 text-white bg-red-600 rounded-full baseline hover:bg-red-400"
        >Get Started</a
      >
    </div>
  </nav>
</template>
