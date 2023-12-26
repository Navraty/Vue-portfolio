<script setup>
import { RouterLink, RouterView } from 'vue-router'
</script>

<template>
       <!-- les Skills -->

  <div class="py-10 px-10">
      <div class="flex flex-col items-center  
                  lg:flex-row lg:items-center lg:flex lg:flex-col
                  md:flex-row md:items-center md:flex md:flex-col">

        <span class="font-bold text-[#0077FF] ">SERVICES</span>
        <span class="font-bold text-3xl py-2">Exploring My Design <span class="font-bold text-3xl text-[#0077FF]">Skills</span></span>
        <span class="text-semibold flex ">We transform you ideas into a distinctive web project that both inspires <br>
           </span> <span class="">you and captivates your customes</span>
      </div>

      <div class="grid gap-3 py-3
                  lg:grid lg:grid-cols-4 lg:gap-4 lg:py-20
                  md:grid md:grid-cols-2 md:gap-4 md:py-20">

        <div class="bg-[#0077FF] rounded-lg px-5 py-6  ">
            <img src="../assets/icon.png" class="w-[200px] " alt="">
            <span class="font-bold text-white">Website / App Design <br>UX /UI Design </span>
            <p class="text-white text-sm">Creating Engaging Digital Experiences <br>
              for Websites and Apps through UX/UI <br>Design</p>
               <button class="text-white flex items-center gap-3">Learn more <img src="../assets/Arrow 1 (3).png" alt=""></button>
           
              
        </div>

        <div class="border border-gray-200 rounded-lg px-5 py-6 shadow-lg  hover:bg-[#0077FF] hover:text-white">
            <img src="../assets/front1.png" class="w-[50px] " alt="">
            <span class="font-bold text-black">Website / App Design <br>UX /UI Design </span>
            <p class="text-black text-semi-bold text-black text-sm">Creating Engaging Digital Experiences <br>
              for Websites and Apps through UX/UI <br>Design
            </p>
            <button class="text-[#0077FF] flex items-center gap-3">Learn more <img src="../assets/Arrow 1 (2).png" alt=""></button>
        </div>

        <div class="border border-gray-200 rounded-lg px-5 py-6 shadow-lg  hover:bg-[#0077FF] hover:text-white border border-[#0077FF]">
            <img src="../assets/front1.png" class="w-[50px]" alt="">
            <span class="font-bold text-black">Website / App Design <br>UX /UI Design </span>
            <p class="text-black text-semi-bold text-black text-sm">Creating Engaging Digital Experiences <br>
              for Websites and Apps through UX/UI <br>Design
            </p>
            <button class="text-[#0077FF] flex items-center gap-3">Learn more <img src="../assets/Arrow 1 (2).png" alt=""></button>
        </div>

        <div class="border border-gray-200 rounded-lg px-5 py-6 shadow-lg hover:bg-[#0077FF] hover:text-white border border-[#0077FF]">
            <img src="../assets/front1.png" class="w-[50px]" alt="">
            <span class="font-bold text-black">Website / App Design <br>UX /UI Design </span>
            <p class="text-black text-semi-bold text-black text-sm">Creating Engaging Digital Experiences <br>
              for Websites and Apps through UX/UI <br>Design
            </p>
            <button class="text-[#0077FF] flex items-center gap-3">Learn more <img src="../assets/Arrow 1 (2).png" alt=""></button>
        </div>
      </div>
  </div>
</template>

<!-- <script>
export default {

}
</script> -->

<style>

</style>