<template>
  <div class="home">
    <section class="bg-white mt-20">
      <div class="max-w-2xl px-6 text-center mx-auto">
        <h2 class="text-3xl font-semibold text-gray-800">
          Hi,
          <span class="bg-indigo-600 text-white rounded px-1">I’m Patcharapon Chatsomboonchai</span> .
          <br />Nice to meet you.
        </h2>
        <p class="text-gray-600 mt-4">Hello. This website for test VueJS.</p>

        <div class="flex items-end justify-center mt-16">
          <img
            class="rounded-full h-32 w-32 mb-8"
            src="https://my-blog.beforesecond.now.sh/img/me.jpg"
          />
        </div>
      </div>
    </section>
    <section class="bg-gray-800 pattern py-20">
      <div class="max-w-5xl px-6 mx-auto text-center">
        <h2 class="text-2xl font-semibold text-white">About Me</h2>

        <p class="text-gray-400 mt-2">Name : Patcharapon Chatsomboonchai</p>
        <p class="text-gray-400 mt-2">Nickname : First</p>
        <p class="text-gray-400 mt-2">Email : firstnaruto038@gmail.com</p>
        <p
          class="text-gray-400 mt-2"
        >Skill : React , Angular , NodeJS , Golang , AWS , Firebase , etc.</p>
      </div>
    </section>
    <Framework></Framework>
  </div>
</template>

<script>
// @ is an alias to /src
import Framework from '@/components/Framework.vue'

export default {
  name: 'Home',
  components: {
    Framework
  }
}
</script>
