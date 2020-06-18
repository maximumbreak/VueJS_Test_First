<template>
  <div class="flex justify-center w-full bg-gray-200">
    <div class="max-w-4xl px-10 my-4 py-6 bg-white rounded-lg shadow-md">
      <div class="flex justify-between items-center">
        <span class="font-light text-gray-600">{{ date }}</span>
        <a
          class="px-2 py-1 bg-gray-600 text-gray-100 font-bold rounded hover:bg-gray-500"
          v-bind:href="link"
        >Dev</a>
      </div>
      <div class="mt-2">
        <a
          class="text-2xl text-gray-700 font-bold hover:text-gray-600"
          v-bind:href="link"
        >{{ title }}</a>
        <p class="mt-2 text-gray-600">{{ desc }}</p>
      </div>
      <div class="flex justify-between items-center mt-4">
        <a class="text-blue-600 hover:underline" v-bind:href="link">Read more</a>
        <div>
          <a class="flex items-center" href="https://dev.to/beforesecond">
            <img
              class="mx-4 w-10 h-10 object-cover rounded-full hidden sm:block"
              src="https://my-blog.beforesecond.now.sh/img/me.jpg"
              alt="avatar"
            />
            <h1 class="text-gray-700 font-bold">Patcharapon</h1>
          </a>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  components: 'Acticle',
  props: {
    date: String,
    title: String,
    desc: String,
    link: String
  }
}
</script>