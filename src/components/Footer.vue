<script setup>
import { RouterLink, RouterView } from 'vue-router'
</script>

<template>
       <div class=" mt-8 flex flex-col text-white items-center bg-[#0077FF] py-5 ">
      <h2 class="font-bold text-xl mb-2">CONTACT ME</h2>
      <h1 class="font-bold text-3xl mb-2">Request Free Consultancy</h1>
        </div>
  <footer class="bg-[#0077FF]">
    <div class="flex flex-col py-4 px-3
                lg:grid lg:grid-cols-2 lg:gap-4 lg:px-10 lg:justify-arround 
                md:grid md:grid-cols-2 md:gap-4 md:px-10 md:justify-arround md:py-5">

      <div class="bg-white text-black rounded-lg h-[22em] px-6 mb-5 ">  
        <p class="font-bold text-1xl mt-5">Hotline 24/7:</p>
        <p class="font-bold text-3xl">(+23) 5535 68 68</p>
        <p class="mt-14 "><b>Address:</b>3727 Westheimer Rd., Santa Ana, Illinois 65486</p> 
        <p class="mt-2"><b>Email:</b> info@example.com</p>
        <p class="mt-2"><b>Work Hours:</b> Mon - Sat : 10:00 - 18:00</p>
      </div>

      <form class="grid gap-3 lg:gap-6">

        <div class="flex flex-col gap-3 py-3
                    lg:flex-row lg:justify-between
                    md:flex md:justify-between md:gap-2">

                    <input class="py-3 px-4 text-white rounded lg:w-1/2" type="email" placeholder="Email Address*">
                    <input class="py-3 px-4 text-white rounded lg:w-1/2" type="text" placeholder="Name*">
         </div>

          <textarea class="py-3 px-4 text-white rounded h-[50px]" placeholder="How can we help you?"></textarea>
          <textarea class="py-3 px-4 text-white rounded h-[11em] mt-2" placeholder="How can we help you?"></textarea>
          <div>
              <input type="checkbox" id="terms">
              <label for="terms" class="ml-2 text-white">By submitting, I agree to the Terms & Conditions</label>
        </div>
          <button class="py-2 px-4 bg-blue-800 hover:bg-[#0077FF] text-white font-bold rounded-full lg:w-1/2">Request Now</button>
      </form>
    </div>

    <div class="flex flex-col items-center
                lg:flex-row lg:justify-between">

      <div class = "flex text-white flex-col items-center gap-2
                    lg:flex-row lg:gap-5 lg:items-center lg:px-10 lg:text-white
                    md:flex md:gap-5 md:items-center md:px-10 md:text-white">

        <a href="#"><img src="./assets/Group 8.png" alt=""></a>
        <a href="" class="font-bold">AeroVision</a>
        <p>© AeroVision | ©2021 All rights reserved.</p>
      </div>  
          
      <div class="text-white flex gap-5 py-2 items-center
                  lg:text-white lg:flex lg:px-10">
            <span>© FOLLOW US:</span>
        <div class="flex gap-2">
              <img src="../assets/facebook icon.png" alt="">
              <img src="../assets/Group 7.png" alt="">
              <img src="../assets/icon linkedin.png" alt="">
              <img src="../assets/icon email.png" alt="">
        </div>
      </div>
    </div>
  </footer>
</template>
<!-- 
<script>
export default {

}
</script> -->

<style>

</style>