<template>
<div class="bg-lime-tourgather">
  <div id="feature" class="px-4 py-16 mx-auto sm:max-w-xl md:max-w-full lg:max-w-screen-xl md:px-24 lg:px-8 lg:py-20">
    <div class="max-w-xl mt-10 mb-10 md:mx-auto text-center lg:max-w-2xl md:mb-12">
      <h2 class="max-w-lg mb-6 font-sans text-3xl font-bold leading-none tracking-tight text-gray-900 sm:text-4xl md:mx-auto">
        <span class="relative inline-block">
          <svg viewBox="0 0 52 24" fill="currentColor" class="absolute top-0 left-0 z-0 hidden w-32 -mt-8 -ml-20 text-blue-gray-100 lg:w-32 lg:-ml-28 lg:-mt-10 sm:block">
            <defs>
              <pattern id="bfcc89c7-3b4a-491a-bc7e-53e26502ff69" x="0" y="0" width=".135" height=".30">
                <circle cx="1" cy="1" r=".7"></circle>
              </pattern>
            </defs>
            <rect fill="url(#bfcc89c7-3b4a-491a-bc7e-53e26502ff69)" width="52" height="24"></rect>
          </svg>
          <span class="relative">Apa </span>
        </span>
        saja yang bisa dilakukan di
        <span class="inline-block text-purple-tourgather">TOURGATHER</span>
      </h2>
      <p class="text-base text-gray-700 md:text-lg">
        <br>
      </p>
    </div>
    <div class="grid gap-8 row-gap-8 lg:grid-cols-3">
      <div class="items-center">
        <div class="flex items-center justify-center w-48 h-48 mx-auto lg:w-80 lg:h-80 ">
          <img class="object-cover" src="@/assets/hand-phone.webp" alt="" />
        </div>
        <h6 class="mb-2 font-semibold leading-5 text-center">Rancang dan buat Open Trip mu sendiri</h6>
        <p class="max-w-md mb-3 text-sm text-gray-900 sm:mx-auto">
          
        </p>
        
      </div>
      <div class="text-center">
        <div class="flex items-center justify-center w-48 h-48 mx-auto lg:w-80 lg:h-80">
          <img class="object-cover" src="@/assets/guide.webp" alt="" />
        </div>
        <h6 class="mb-2 font-semibold leading-5">Jadi travel buddy 
          <br> dan dapatkan uang tambahan</h6>
        <p class="max-w-md mb-3 text-sm text-gray-900 sm:mx-auto">
          
        </p>
        
      </div>
      <div class="text-center">
        <div class="flex items-center justify-center w-48 h-48 mx-auto lg:w-80 lg:h-80">
          <img class="object-cover" src="@/assets/friend.webp" alt="" />
        </div>
        <h6 class="mb-2 font-semibold leading-5">Ikuti Open Trip dan temukan teman baru 
          <br>untuk traveling bersama</h6>
        <p class="max-w-md mb-3 text-sm text-gray-900 sm:mx-auto">
          
        </p>
        
      </div>
    </div>
  </div>
</div>
</template>

<script>
export default {
  name : "BodyFeature"
};
</script>