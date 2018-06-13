<template>
  <div class="hello text-center">
    <h1 class="mb-4">{{ msg }}</h1>
    <h2 class="mb-4">Essential Links</h2>
    <ul class="list-reset flex item-center justify-center max-w-md mx-auto">
      <li class="text-xl bg-grey-lighter py-1 px-4 rounded-full mr-2">
        <a
          href="https://vuejs.org"
          target="_blank"
          class="no-underline text-white"
        >
          Vue
        </a>
      </li>
      <li class="text-xl bg-grey-lighter py-1 px-4 rounded-full mr-2">
        <a
          href="https://tailwindcss.com"
          target="_blank"
          class="no-underline text-white"
        >
          Tailwind
        </a>
      </li>
      <li class="text-xl bg-grey-lighter py-1 px-4 rounded-full ">
        <a
          href="https://www.zondicons.com"
          target="_blank"
          class="no-underline text-white"
        >
          Zondicons
        </a>
      </li>

    </ul>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  data () {
    return {
      msg: 'Welcome to Your Vue.js and Tailwind Starter Kit'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style>

</style>