<script setup lang="ts">

</script>

<template>
  <div class="lg:w-1/2 md:w-2/3 mx-auto">
    <div class="flex flex-wrap -m-2">
      <div class="p-2 w-1/2">
        <div class="relative">
          <label for="name" class="leading-7 text-sm text-gray-600">Rue</label>
          <input type="text" id="name" name="name" class="w-full bg-gray-100 bg-opacity-50 rounded border border-gray-300 focus:border-yellow-500 focus:bg-white focus:ring-2 focus:ring-yellow-200 text-base outline-none text-gray-700 py-1 px-3 leading-8 transition-colors duration-200 ease-in-out">
        </div>
      </div>
      <div class="p-2 w-1/2">
        <div class="relative">
          <label for="email" class="leading-7 text-sm text-gray-600">Ville</label>
          <input type="email" id="email" name="email" class="w-full bg-gray-100 bg-opacity-50 rounded border border-gray-300 focus:border-yellow-500 focus:bg-white focus:ring-2 focus:ring-yellow-200 text-base outline-none text-gray-700 py-1 px-3 leading-8 transition-colors duration-200 ease-in-out">
        </div>
      </div>
    </div>
  </div>
</template>