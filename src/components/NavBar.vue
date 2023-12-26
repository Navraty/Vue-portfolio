<!-- <script setup>
import { RouterLink, RouterView } from 'vue-router'
</script> -->
 <!-- <div>
        <RouterLink to="/">Home</RouterLink>
        <RouterLink to="/about">About</RouterLink>
      </div> -->

<template>
   


  <nav class="flex justify-between py-3 px-10 gap-2">

    <div class = "flex gap-5 items-center px-10">
        <a href="#"><img src="../assets/Group 8.png" alt=""></a>
        <a href="" class="font-bold">AeroVision</a>
    </div>

    <div class="hidden 
                lg:flex-row lg:gap-10 lg:items-center lg:font-bold
                md:flex md:gap-10 md:items-center">

      <a href="">Home</a>
      <a href="">About Me</a>
      <a href="">Service</a>
      <a href="">Blog</a>
      <a href="">Contact Me</a>

      <button class="text-white px-6 bg-[#0077FF] py-2 rounded-full hover:bg-white hover:text-[#0077FF] border border-[#0077FF]">
        Let's chat
      </button>
    </div>
    <img src="./assets/menu.png" class="w-[40px] lg:hidden" alt="menu">
  </nav>
</template>