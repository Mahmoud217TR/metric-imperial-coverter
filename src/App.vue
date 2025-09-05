<script setup>
  
</script>

<template>
  <header class="pt-20 pb-10">
    <h1 class="text-center text-4xl">
      Metric-Imperial Converter
    </h1>
  </header>

  <main class="flex flex-col gap-12 my-20 container mx-auto">
    <div class="bg-white text-gray-800 p-4 rounded-md w-full max-w-md mx-auto">
      <div class="">
        <h2 class="text-2xl font-semibold">
          Length
        </h2>
      </div>
    </div>
  </main>

  <footer class="my-10 px-4">
    <div class="container mx-auto">
      <hr class="opacity-25 mb-8">
      <p class="text-center text-2xl">
        Copyright © 2025 All Rights Reserved -
        <a href="https://github.com/Mahmoud217TR" target="__blank"
          class="hover:text-amber-500 transition-colors duration-300">
          MahmoudTR
        </a>
      </p>
    </div>
  </footer>
  <ToastNotification />
</template>

<script>
export default {
  name: "App",
}
</script>
