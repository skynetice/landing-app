<template>
<div class="relative bg-purple-tourgather">
  <div
    class="px-4 py-3 mx-auto sm:max-w-xl md:max-w-full lg:max-w-screen-xl md:px-24 lg:px-8"
  >
    <div class="relative flex items-center justify-between">
      <a
        href="/"
        aria-label="tourgather"
        title="Tourgather"
        class="inline-flex items-center"
      >
      <img class="object-cover w-1/3 lg:w-1/6" src="@/assets/tourgather-white.webp" alt="">
      </a>
      <ul class="flex items-center hidden space-x-8 lg:flex">
        <li>
          <a
            href="/"
            aria-label="instagram"
            title="Instagram"
            class="font-medium tracking-wide text-white transition-colors duration-200 hover:text-teal-accent-400"
            >
            <i class="fab fa-instagram fa-lg"></i>
             </a
          >
        </li>
        <li>
          <a
            href="/"
            aria-label="twitter"
            title="Twitter"
            class="font-medium tracking-wide text-white transition-colors duration-200 hover:text-teal-accent-400"
            >
            <i class="fab fa-twitter fa-lg"></i>
             </a
          >
        </li>
        <li>
          <a
            href="/"
            aria-label="facebook"
            title="Facebook"
            class="font-medium tracking-wide text-white transition-colors duration-200 hover:text-teal-accent-400"
            > 
            <i class="fab fa-facebook fa-lg"></i>
            </a
          >
        </li>
        <li>
          <a
            href="/"
            aria-label="linkedin"
            title="LinkedIn"
            class="font-medium tracking-wide text-white transition-colors duration-200 hover:text-teal-accent-400"
            > 
            <i class="fab fa-linkedin fa-lg"></i>
            </a
          >
        </li>
        <li>
          <a
            href="/"
            class="font-medium tracking-wide text-gray-700 transition-colors duration-200 hover:text-deep-purple-accent-400"
            aria-label="Sign up"
            title="Sign up"
          >
             
          </a>
        </li>
      </ul>
      <div class="lg:hidden">
        <button
          aria-label="Open Menu"
          title="Open Menu"
          class="p-2 -mr-1 transition duration-200 rounded focus:outline-none focus:shadow-outline hover:bg-deep-purple-50 focus:bg-deep-purple-50"
          @click="isMenuOpen = true"
        >
          <svg class="w-5 text-white" viewBox="0 0 24 24">
            <path
              fill="currentColor"
              d="M23,13H1c-0.6,0-1-0.4-1-1s0.4-1,1-1h22c0.6,0,1,0.4,1,1S23.6,13,23,13z"
            ></path>
            <path
              fill="currentColor"
              d="M23,6H1C0.4,6,0,5.6,0,5s0.4-1,1-1h22c0.6,0,1,0.4,1,1S23.6,6,23,6z"
            ></path>
            <path
              fill="currentColor"
              d="M23,20H1c-0.6,0-1-0.4-1-1s0.4-1,1-1h22c0.6,0,1,0.4,1,1S23.6,20,23,20z"
            ></path>
          </svg>
        </button>
        <div v-if="isMenuOpen" class="absolute top-0 left-0 w-full z-10">
          <div class="p-5 bg-white border rounded shadow-sm pb-12">
            <div class="flex mb-4 justify-end">
              <div>
                <button
                  aria-label="Close Menu"
                  title="Close Menu"
                  class="p-2 -mt-2 -mr-2 transition duration-200 rounded hover:bg-gray-200 focus:bg-gray-200 focus:outline-none focus:shadow-outline"
                  @click="isMenuOpen = false"
                >
                  <svg class="w-5 text-purple-tourgather" viewBox="0 0 24 24">
                    <path
                      fill="currentColor"
                      d="M19.7,4.3c-0.4-0.4-1-0.4-1.4,0L12,10.6L5.7,4.3c-0.4-0.4-1-0.4-1.4,0s-0.4,1,0,1.4l6.3,6.3l-6.3,6.3 c-0.4,0.4-0.4,1,0,1.4C4.5,19.9,4.7,20,5,20s0.5-0.1,0.7-0.3l6.3-6.3l6.3,6.3c0.2,0.2,0.5,0.3,0.7,0.3s0.5-0.1,0.7-0.3 c0.4-0.4,0.4-1,0-1.4L13.4,12l6.3-6.3C20.1,5.3,20.1,4.7,19.7,4.3z"
                    ></path>
                  </svg>
                </button>
              </div>
            </div>
            <div class="mb-12">
                <a
                  href="/"
                  aria-label="Tourgather"
                  title="Tourgather"
                  class="inline-flex items-center"
                >
                  <img class="object-cover w-1/2 mx-auto" src="@/assets/tourgather.webp" alt="">
                </a>
              </div>
            <nav>
              <ul class="flex flex-col space-y-8 items-center">
                <li>
                  <a
                    href="/"
                    aria-label="instagram"
                    title="Instagram"
                    class="font-medium tracking-wide text-purple-tourgather transition-colors duration-200 hover:text-teal-accent-400"
                    >
                    <i class="fab fa-instagram fa-lg"></i>
                    </a
                  >
                </li>
                <li>
                  <a
                    href="/"
                    aria-label="twitter"
                    title="Twitter"
                    class="font-medium tracking-wide text-purple-tourgather transition-colors duration-200 hover:text-teal-accent-400"
                    >
                    <i class="fab fa-twitter fa-lg"></i>
                    </a
                  >
                </li>
                <li>
                  <a
                    href="/"
                    aria-label="facebook"
                    title="Facebook"
                    class="font-medium tracking-wide text-purple-tourgather transition-colors duration-200 hover:text-teal-accent-400"
                    > 
                    <i class="fab fa-facebook fa-lg"></i>
                    </a
                  >
                </li>
                <li>
                  <a
                    href="/"
                    aria-label="linkedin"
                    title="LinkedIn"
                    class="font-medium tracking-wide text-purple-tourgather transition-colors duration-200 hover:text-teal-accent-400"
                    > 
                    <i class="fab fa-linkedin fa-lg"></i>
                    </a
                  >
                </li>
              </ul>
            </nav>
          </div>
        </div>
      </div>
    </div>
  </div>
</div>  
</template>

<script>
export default {
  data() {
    return {
      isMenuOpen: false,
    };
  },
  name : "NavTop"
};
</script>