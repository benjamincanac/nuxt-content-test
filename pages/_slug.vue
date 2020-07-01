<template>
  <div class="flex flex-wrap-reverse">
    <div class="w-full lg:w-3/4 py-4 lg:p-8 lg:border-r">
      <article>
        <h1 class="text-4xl font-black mb-4 leading-none">{{ document.title }}</h1>
        <nuxt-content :document="document" />
      </article>
    </div>
    <div class="w-full lg:w-1/4 py-4 lg:p-8">
      <p class="mb-4 text-gray-500 uppercase font-bold text-sm">On this page</p>
      <nav>
        <!-- TODO: Toc -->
        <ul>
          <li>...</li>
        </ul>
      </nav>
    </div>
  </div>
</template>

<script>
export default {
  data () {
    return {
      document: {}
    }
  }
}
</script>
