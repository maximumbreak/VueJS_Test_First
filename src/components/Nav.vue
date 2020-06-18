<template>
  <nav class="flex items-center justify-between flex-wrap bg-teal-500 p-6">
    <div class="flex items-center flex-shrink-0 text-white mr-6 bg-transparent">
      <span class="font-semibold text-xl tracking-tight">First Portfolio Beta</span>
    </div>
    <div class="block lg:hidden">
      <button
        class="flex items-center px-3 py-2 border rounded text-teal-200 border-teal-400 hover:text-white hover:border-white"
      >
        <svg class="fill-current h-3 w-3" viewBox="0 0 20 20" xmlns="http://www.w3.org/2000/svg">
          <title>Menu</title>
          <path d="M0 3h20v2H0V3zm0 6h20v2H0V9zm0 6h20v2H0v-2z" />
        </svg>
      </button>
    </div>
    <div class="w-full block flex-grow lg:flex lg:items-center lg:w-auto">
      <div class="text-sm lg:flex-grow">
        <!-- <a class="block mt-4 lg:inline-block lg:mt-0 text-teal-200 hover:text-white mr-4">
          <router-link to="/">Home</router-link>
        </a>-->
      </div>
    </div>
    <div class="flex items-center -mx-2">
      <a
        class="flex items-center mx-2 text-gray-800 hover:text-indigo-600"
        href="https://my-blog.beforesecond.now.sh"
      >
        <svg
          class="h-5 w-5 sm:h-6 sm:w-6 fill-current"
          xmlns="http://www.w3.org/2000/svg"
          viewBox="0 0 512 512"
        >
          <path
            d="m444.464844 4.394531c-5.855469-5.859375-15.355469-5.859375-21.210938 0l-115.605468 115.605469h-262.148438c-24.8125 0-45 20.1875-45 45v209.996094c0 24.816406 20.1875 45 45 45h16v77c0 6.097656 3.691406 11.589844 9.335938 13.890625 5.726562 2.335937 12.183593.894531 16.386718-3.398438l85.585938-87.492187h174.691406c24.8125 0 45-20.183594 45-45v-170.144532l115.605469-115.605468c5.855469-5.859375 5.855469-15.355469 0-21.214844zm-137.886719 243.949219-42.425781-42.425781 127.28125-127.277344 42.425781 42.425781zm-58.40625-15.980469 31.960937 31.960938-54.78125 22.820312zm114.328125 142.632813c0 8.273437-6.730469 15-15 15h-181c-4.035156 0-7.902344 1.628906-10.722656 4.511718l-64.277344 65.707032v-55.21875c0-8.28125-6.714844-15-15-15h-31c-8.269531 0-15-6.726563-15-15v-209.996094c0-8.273438 6.730469-15 15-15h232.144531l-45.3125 45.3125c-1.25 1.25-2.488281 2.972656-3.3125 5.011719l-41.519531 99.675781h-81c-8.285156 0-15 6.714844-15 15 0 8.28125 6.714844 14.988281 15 14.988281h90.992188.011718c1.929688 0 4-.394531 5.894532-1.207031l108.773437-45.304688c1.8125-.707031 3.640625-1.9375 5.015625-3.3125l45.3125-45.3125zm92.570312-275.144532-42.425781-42.425781 21.214844-21.210937 42.425781 42.425781zm0 0"
          />
        </svg>
      </a>
    </div>
    <div class="flex items-center -mx-2">
      <a
        class="flex items-center mx-2 text-gray-800 hover:text-indigo-600"
        href="https://github.com/beforesecond"
      >
        <svg
          class="h-5 w-5 sm:h-6 sm:w-6 fill-current"
          xmlns="http://www.w3.org/2000/svg"
          viewBox="0 0 512 512"
        >
          <path
            d="M256,32C132.3,32,32,134.9,32,261.7c0,101.5,64.2,187.5,153.2,217.9a17.56,17.56,0,0,0,3.8.4c8.3,0,11.5-6.1,11.5-11.4,0-5.5-.2-19.9-.3-39.1a102.4,102.4,0,0,1-22.6,2.7c-43.1,0-52.9-33.5-52.9-33.5-10.2-26.5-24.9-33.6-24.9-33.6-19.5-13.7-.1-14.1,1.4-14.1h.1c22.5,2,34.3,23.8,34.3,23.8,11.2,19.6,26.2,25.1,39.6,25.1a63,63,0,0,0,25.6-6c2-14.8,7.8-24.9,14.2-30.7-49.7-5.8-102-25.5-102-113.5,0-25.1,8.7-45.6,23-61.6-2.3-5.8-10-29.2,2.2-60.8a18.64,18.64,0,0,1,5-.5c8.1,0,26.4,3.1,56.6,24.1a208.21,208.21,0,0,1,112.2,0c30.2-21,48.5-24.1,56.6-24.1a18.64,18.64,0,0,1,5,.5c12.2,31.6,4.5,55,2.2,60.8,14.3,16.1,23,36.6,23,61.6,0,88.2-52.4,107.6-102.3,113.3,8,7.1,15.2,21.1,15.2,42.5,0,30.7-.3,55.5-.3,63,0,5.4,3.1,11.5,11.4,11.5a19.35,19.35,0,0,0,4-.4C415.9,449.2,480,363.1,480,261.7,480,134.9,379.7,32,256,32Z"
          />
        </svg>
      </a>
    </div>
    <!-- <div class="w-full block flex-grow lg:flex lg:w-auto mr-1 justify-end">
      <div class="px-1">
        <a
          class="inline-block text-sm px-4 py-2 leading-none border rounded text-white border-white hover:border-transparent hover:text-teal-500 hover:bg-white mt-4 lg:mt-0"
        >
          <router-link to="/login">Login</router-link>
        </a>
      </div>
      <div class="px-1">
        <a
          class="inline-block text-sm px-4 py-2 leading-none border rounded text-white border-white hover:border-transparent hover:text-teal-500 hover:bg-white mt-4 lg:mt-0"
        >
          <router-link to="/register">Register</router-link>
        </a>
      </div>
    </div>-->
  </nav>
</template>

<script>
export default {
  name: 'Nav'
}
</script>
