<template>
  <nav>
    <!-- desktop menu -->
    <div class="bg-[radial-gradient(ellipse_at_top_left,_var(--tw-gradient-stops))] from-gray-700 via-gray-900 to-black">
        <div class="mx-auto max-w-7xl">
            <div class="flex justify-between">
                <!-- menu -->
                <div class="flex space-x-4">
                  <!-- logo -->
                    <a href="" class="flex items-start px-2 py-5 space-x-2">
                      <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="h-8 text-white w-9">
                        <path stroke-linecap="round" stroke-linejoin="round" d="M20.893 13.393l-1.135-1.135a2.252 2.252 0 01-.421-.585l-1.08-2.16a.414.414 0 00-.663-.107.827.827 0 01-.812.21l-1.273-.363a.89.89 0 00-.738 1.595l.587.39c.59.395.674 1.23.172 1.732l-.2.2c-.212.212-.33.498-.33.796v.41c0 .409-.11.809-.32 1.158l-1.315 2.191a2.11 2.11 0 01-1.81 1.025 1.055 1.055 0 01-1.055-1.055v-1.172c0-.92-.56-1.747-1.414-2.089l-.655-.261a2.25 2.25 0 01-1.383-2.46l.007-.042a2.25 2.25 0 01.29-.787l.09-.15a2.25 2.25 0 012.37-1.048l1.178.236a1.125 1.125 0 001.302-.795l.208-.73a1.125 1.125 0 00-.578-1.315l-.665-.332-.091.091a2.25 2.25 0 01-1.591.659h-.18c-.249 0-.487.1-.662.274a.931.931 0 01-1.458-1.137l1.411-2.353a2.25 2.25 0 00.286-.76m11.928 9.869A9 9 0 008.965 3.525m11.928 9.868A9 9 0 118.965 3.525" />
                      </svg><span class="ml-2 text-2xl font-extrabold text-white">iCanlk</span>
                    </a>
                  <!-- menu -->
                  <div class="items-center hidden space-x-1 md:flex">
                    <a href="#" class="px-2 py-5 text-white cursor-pointer hover:text-yellow-500">Home</a>
                    <a href="#" class="px-2 py-5 text-white cursor-pointer hover:text-yellow-500">Reach Us</a>
                    
                    
                  </div>
                </div>
                <!-- login -->
                <div class="items-center hidden space-x-1 md:flex">
                  <a href="#" class="px-2 py-5 text-white cursor-pointer hover:text-yellow-500">Language</a>
                </div>
                <!-- show mobile menu -->
                <div class="flex items-center md:hidden">
                  <button @click="showMobileMenu = !showMobileMenu" class="px-2 py-5">
                    <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="w-8 h-8 text-white">
                      <path stroke-linecap="round" stroke-linejoin="round" d="M3.75 6.75h16.5M3.75 12h16.5m-16.5 5.25h16.5" />
                    </svg>
                    
                  </button>
                </div>
            </div>
        </div>
    </div>
    <!-- mobile menu -->
    <div class="bg-indigo-700 md:hidden" :class="{hidden: showMobileMenu}">
      <a href="#" class="block px-4 py-2 text-white hover:bg-indigo-600 hover:text-bg-yellow-500">Home</a>
      <a href="#" class="block px-4 py-2 text-white hover:bg-indigo-600 hover:text-bg-yellow-500">Reach Us</a>
      <!-- <button-component /> -->
    </div>
  </nav>
  <!-- <div class="p-8 text-2xl font-extrabold text-center">Content</div> -->
</template>

<script setup>
  import { ref } from 'vue';
  // import ButtonComponent from './ButtonComponent.vue';

  const showMobileMenu = ref(true)
  
</script>

<style>

</style>