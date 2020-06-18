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
    <div class="flex justify-center bg-gray-200 py-8">
      <h2 class="text-3xl font-semibold text-gray-800">
        <span class="text-gray-600 rounded px-1">Last Post</span>
      </h2>
    </div>
    <Article
      title="มาใช้ Package management สำหรับ deno กันเถอะ"
      desc="หลังจากที่ผมได้ลองเล่น Deno มาได้สักพักก็ไปนึกถึง npm ที่เป็น Package management แล้วก็มาเจอ Trex ซึ่งอ่านว่าทีเร็กซ์ นั้นเป็นตัวจัดการที่ทำหน้าที่คล้าย npm เลย แต่ก็มีสิ่งที่เราต้องรู้จักก่อนที่จะใช้ Trex นั่นคือ import_map.json"
      link="https://dev.to/beforesecond/package-management-deno-19n0"
    ></Article>
    <Article
      title="มาลองเล่น Deno GraphQL พร้อมกับทำ Deno Hot Reload กันเถอะ"
      desc="มาวันนี้หลาย ๆ คนก็น่าจะรู้จัก Deno มาสักพักแล้ว Deno เป็น Runtime ตัวใหม่ของ
Javascript ที่จะมาแทน Node ในอนาคตสำหรับใครยังไม่ได้ติดตั้ง Deno ไปติดตั้งกันเลยดีกว่า"
      link="https://dev.to/beforesecond/deno-graphql-deno-hot-reload-29mb"
    ></Article>
    <Article
      title="มาลองใช้ NestJS ทำ GraphQL Server กัน (ฉบับผู้เริ่มต้น)"
      desc="ทุกวันนี้ผมใช้ express + apollo ทำ GraphQL Server แต่ปีนี้ในทีมก็มีมติว่าจะเปลี่ยนไปเขียน TypeScript ซึ่งจะตอบโจทย์ในเรื่องของ NewBie Mistakes ตอนแรกว่าจะเขียนไว้อ่านเอง แต่ก็อยากมาแชร์ให้ทุก ๆ คนมาลองดูกันครับ"
      link="https://dev.to/beforesecond/nestjs-graphql-server-36o6"
    ></Article>
  </div>
</template>

<script>
// @ is an alias to /src
import Framework from '@/components/Framework.vue'
import Article from '@/components/Article.vue'

export default {
  name: 'Home',
  components: {
    Framework,
    Article
  }
}
</script>
