<template>
  <div class="flex justify-center align-center">
    <div class="w-full max-w-md">
      <form class="bg-white shadow-md rounded px-8 pt-6 pb-8 mb-4">
        <div class="mb-4">
          <label
            class="block text-gray-700 text-sm font-bold mb-2"
            for="username"
          >
            Username
          </label>
          <input
            class="shadow appearance-none border rounded w-full py-2 px-3 text-gray-700 leading-tight focus:outline-none focus:shadow-outline"
            id="username"
            type="text"
            placeholder="Username"
          />
        </div>
        <div class="mb-6">
          <label
            class="block text-gray-700 text-sm font-bold mb-2"
            for="password"
          >
            Password
          </label>
          <input
            class="shadow appearance-none border  rounded w-full py-2 px-3 text-gray-700 mb-3 leading-tight"
            id="password"
            placeholder="Password"
            type="password"
          />
        </div>
        <div class="flex items-center justify-between">
          <button
            class="bg-teal-500 hover:bg-teal-700 text-white font-bold py-2 px-4 rounded"
            type="button"
          >
            Sign In
          </button>
          <a
            class="inline-block align-baseline font-bold text-sm text-teal-500 hover:text-teal-800"
            href="#"
          >
            Forgot Password?
          </a>
        </div>
      </form>
    </div>
  </div>
</template>

<script>
export default {
  name: 'Login'
}
</script>
