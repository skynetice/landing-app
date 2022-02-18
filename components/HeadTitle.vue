<template>
<div class="">
  <svg class="relative w-full z-0" id="visual" viewBox="0 0 900 50" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" version="1.1"><rect x="0" y="0" width="900" height="50" fill="#fff"></rect>
  <path d="M0 35L12.5 31.7C25 28.3 50 21.7 75 21.2C100 20.7 125 26.3 150 26.8C175 27.3 200 22.7 225 21.3C250 20 275 22 300 24.7C325 27.3 350 30.7 375 31.8C400 33 425 32 450 31.8C475 31.7 500 32.3 525 30.5C550 28.7 575 24.3 600 22C625 19.7 650 19.3 675 21C700 22.7 725 26.3 750 26.7C775 27 800 24 825 22.5C850 21 875 21 887.5 21L900 21L900 0L887.5 0C875 0 850 0 825 0C800 0 775 0 750 0C725 0 700 0 675 0C650 0 625 0 600 0C575 0 550 0 525 0C500 0 475 0 450 0C425 0 400 0 375 0C350 0 325 0 300 0C275 0 250 0 225 0C200 0 175 0 150 0C125 0 100 0 75 0C50 0 25 0 12.5 0L0 0Z" fill="#A352F5" stroke-linecap="round" stroke-linejoin="miter"></path></svg>
  <div class="px-4 pt-4 pb-4 mx-auto sm:max-w-xl md:max-w-full lg:max-w-screen-xl md:px-24 lg:px-8 lg:pt-2 lg:pb-4">
    <div class="flex flex-col items-center justify-between w-full mb-12 lg:mb-8 lg:flex-row">
      <div class="mb-16 lg:mb-0 lg:max-w-lg lg:pr-5 items-center ">
        <div class="max-w-xl mb-6 text-center lg:text-left">
          <h2 class="max-w-lg mb-6 font-sans text-3xl font-bold tracking-tight text-gray-900 sm:text-4xl sm:leading-none">
            Temukan teman baru  <br class="hidden md:block" />
            untuk traveling bareng kamu di 
            <span class="inline-block text-purple-tourgather">TOURGATHER</span>
          </h2>
          <p class="text-base text-gray-700 md:text-lg">
            
          </p>
        </div>
        <div class="flex items-center justify-center lg:justify-start space-x-3">
          <a href="/" class="w-36 transition duration-300 hover:shadow-lg">
            <img src="https://kitwind.io/assets/kometa/app-store.png" class="object-cover object-top w-full h-auto mx-auto" alt="" />
          </a>
          <a href="/" class="w-36 transition duration-300 hover:shadow-lg">
            <img src="https://kitwind.io/assets/kometa/google-play.png" class="object-cover object-top w-full h-auto mx-auto" alt="" />
          </a>
          
        </div>
      </div>
      <div class="flex items-center justify-center lg:w-1/2">
        <div class="w-5/12  lg:ml-64">
          <img class="object-cover animate__animated animate__fadeInUp animate__slower" src="@/assets/phone.webp" alt="" />
        </div>
      </div>
    </div>
    <a
      href="#feature"
      aria-label="Scroll down"
      class="flex items-center justify-center w-10 h-10 mx-auto text-gray-600 duration-300 transform border border-gray-400 rounded-full hover:text-deep-purple-accent-400 hover:border-deep-purple-accent-400 hover:shadow hover:scale-110"
    >
      <svg xmlns="http://www.w3.org/2000/svg" width="12" height="12" viewBox="0 0 12 12" fill="currentColor">
        <path d="M10.293,3.293,6,7.586,1.707,3.293A1,1,0,0,0,.293,4.707l5,5a1,1,0,0,0,1.414,0l5-5a1,1,0,1,0-1.414-1.414Z"></path>
      </svg>
    </a>
  </div>
</div>
</template>

<script>
export default {
  name : "HeadTitle"
};
</script>
