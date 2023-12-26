<script setup>
import NavBar from './components/NavBar.vue';
import Footer from './components/Footer.vue';
import Skills from './components/Skills.vue';
import Temoignage from './components/Temoignage.vue';

</script>

<template>
      <NavBar/>
      <!-- la section hiro -->

  <section class="py-5 flex flex-col px-2">

  <div class="flex flex-col-reverse gap-5 items-center  
              lg:flex-row lg:justify-arround  lg:text-wrap
              md:flex md:justify-between md:items-center">

    <div class="flex px-3 flex-col
                Lg:flex-row lg:flex-col lg:px-10">

      <p class="font-bold">Welcom to my portfolio</p>
      <span class="font-bold text-4xl">Hi I'm </span>
      <span class="font-bold text-[#0077FF] text-4xl">Robert Junior</span>
      <span class="font-bold text-4xl">Product Designer</span>
      <p class="text-gray-700 py-3">
        collaborating with highly skilled individuals,<br>
        our agency delivers top-quality services.
      </p>
      <div class="flex gap-6 py-7">
        <button class="px-3 rounded-full text-white bg-[#0077FF] font-bold  py-2 hover:bg-white hover:text-[#0077FF] border border-[#0077FF]">Hire Me! </button>
        <button class="px-3 rounded-full text-[#0077FF] font-bold border py-2 hover:bg-[#0077FF] hover:text-white flex gap-2">Download Cv <img src="./assets/icon-download 1.png" alt=""> </button>
    
      </div>
    </div>
    <img src="./assets/photo1.png" class="w-[400px]" alt="">
  </div>
  </section>
  <!-- les partenaires -->


  <div class="flex flex-col gap-3 items-center bg-gray-100 
              lg:flex-row lg:bg-gray-100 lg:py-3 lg:px-2">
    <img src="./assets/logo-1.png" alt="">
    <img src="./assets/logo-2.png" alt="">
    <img src="./assets/logo-3 (2).png" alt="">
    <img src="./assets/logo-5.png" alt="">
    <img src="./assets/logo-6.png" alt="">
    
  </div>
  <!-- la section A props -->

  <div class="flex flex-col items-center py-5 px-5
              lg:flex-row lg:justify-arround lg:py-10
              md:flex-row md:justify-evenly md:py-10">

    <img src="./assets/pexels1.png" class="w-[400px]" alt="">

    <div class="">
      <div class=" flex flex-col  py-3 px-5 text-wrap ">
        <span class="text-[#0077FF] text-sm font-bold">ABOUT ME</span><br> 
        <span class="text-[#0077FF] font-bold text-3xl">20 Year's Experience</span><br>
        <span class="font-bold text-3xl">On Product Design</span>
        <p class="py-5">Hello there I'm Robert Junior. I specialize in web design and <br> 
          devlopement , and i"m deeply passionate and committed to my craft <br>
          With 20 years of experiences as a professional graphic designer </p>
      </div>

      <div class="flex flex-col gap-5 px-5 py-3
                  lg:flex-row lg:gap-5 lg:py-12
                  md:flex-row md:gap-5 md:py-12">

        <button class="bg-[#0077FF] rounded-full py-2 text-white px-6 font-bold text-sm hover:bg-white hover:text-[#0077FF] border border-[#0077FF] ">
          Main Skills
        </button>
        <button class="text-[#0077FF] rounded-full py-2 px-6 font-bold text-sm hover:bg-[#0077FF] hover:text-white  border border-[#0077FF]">
          Awards
        </button>
        <button class="text-[#0077FF] rounded-full py-2 px-6 font-bold text-sm border border-[#0077FF] hover:bg-[#0077FF] hover:text-white ">
          Education
        </button>
      </div>
      <!-- la progress-bar -->

    <div class="flex flex-col gap-3 px-5 py-5
                  lg:flex-row lg:flex-col lg:gap-3
                  md:flex md:flex-col md:gap-3">
        <div class=" ">
          <span class="font-bold ">User Experience Design - UI/UX</span>
          <div class="w-full bg-gray-200 rounded-full h-2.5">
            <div class="bg-[#0077FF] h-2.5 rounded-full" style="width: 98%"></div>
            </div>
        </div>

        <div>
          <span class="font-bold ">Web & User Interface Design - Developement</span>
          <div class="w-full bg-gray-200 rounded-full h-2.5">
            <div class="bg-[#0077FF] h-2.5 rounded-full" style="width: 92%"></div>
            </div>
        </div>

        <div>
          <span class="font-bold ">Interface Design - Animation</span>
          <div class="w-full bg-gray-200 rounded-full h-2.5">
            <div class="bg-[#0077FF] h-2.5 rounded-full" style="width: 86%"></div>
            </div>
        </div>
      </div>

    </div>
  </div>
  <!-- les Skills -->
  <Skills/>

  <!-- les projets -->

  <div class="bg-[#0077FF] py-5">
    <div class="flex items-center flex-col py-5">
      <span class="text-sm text-white font-bold">OUR MILESTONES</span>
      <span class="font-bold text-3xl text-white">What sets our studio apart <br></span>
      <span class="font-bold text-3xl text-white">for your projects?</span>
    </div>

    <div class="flex flex-col bg-[#0077FF] gap-5 px-3
                lg:grid lg:grid-cols-4 lg:gap-5 lg:px-10 lg:py-5
                md:grid md:grid-cols-2 md:gap-5 md:px-10 py-5
                ">

      <div class="shadow-lg bg-white rounded-lg items-center flex flex-col g">
        <span class="font-bold text-3xl">8300+</span>
        <span class="">Figma ipsum component <br> variant main layer.Hand</span>
      </div>

      <div class="shadow-lg bg-white rounded-lg items-center flex flex-col">
        <span class="font-bold text-3xl">100%</span>
        <span class="">Figma ipsum component <br> variant main layer.Hand</span>
      </div>

      <div class="shadow-lg bg-white rounded-lg items-center flex flex-col">
        <span class="font-bold text-3xl">3.5k</span>
        <span class="">Figma ipsum component <br> variant main layer.Hand</span>
      </div>

      <div class="shadow-lg bg-white rounded-lg items-center flex flex-col py-3">
        <span class="font-bold text-3xl">240+</span>
        <span class="">Figma ipsum component <br> variant main layer.Hand</span>
      </div>
    </div>

  </div>
  <!-- Our Project -->

  <div class="flex flex-col gap-4 py-8 px-10 items-center">
      <div class="flex flex-col items-center px-5
                    lg:flex-row lg:items-center lg:flex-col lg:py-5
                    md:flex md:items-center md:flex-col md:py-5">

      <span class="text-sm text-[#0077FF] font-bold">OUR PROJECTS</span>
      <span class="font-bold text-3xl text-black">Presenting My Design <br></span>
      <span class="font-bold text-3xl text-black">Porfolio and Case Studies</span>
    </div>

    <div class=" grid grid-cols-2 gap-3
                lg:grid lg:grid-cols-4 gap-10
              md:grid md:grid-cols-2 mdp-10">
        <button class="bg-[#0077FF] rounded-full py-2 text-white px-10 font-bold text-sm  hover:bg-white hover:text-[#0077FF] border border-[#0077FF]">
          All
        </button>
        <button class="text-[#0077FF] rounded-full py-2 px-6 font-bold text-sm  border border-[#0077FF] hover:bg-[#0077FF] hover:text-white  border border-[#0077FF]">
          UI/UX Design
        </button>
        <button class="text-[#0077FF] rounded-full py-2 px-6 font-bold text-sm border border-[#0077FF] hover:bg-[#0077FF] hover:text-white  border border-[#0077FF]">
          Branding Design
        </button>
        <button class="text-[#0077FF] rounded-full px-6 font-bold py-2 text-sm border border-[#0077FF] hover:bg-[#0077FF] hover:text-white  border border-[#0077FF]">
          Wordpress
        </button>
      </div>

      <div class="flex flex-col gap-5
                  lg:grid lg:grid-cols-3 lg:grid-col-col lg:gap-4 
                  md:grid md:grid-col-3 md:px-10 md:py-6">

          <img src="./assets/preview2.png" alt="">
          <img src="./assets/box.png" alt="">
          <img src="./assets/preview3.png" alt="">

          <img src="./assets/box (1).png" alt="">
          <img src="./assets/bloc.png" alt="">
          <img src="./assets/preview6.png" alt="">
        
      </div>
  </div>
  <!-- les temoignages -->
     <Temoignage /> 

  <Footer/>
</template>



