<template>
  <main class="container mx-auto px-4 lg:px-8">
    <div class="flex flex-wrap relative h-screen">
      <aside class="w-full lg:w-1/5 py-4 lg:p-8 lg:border-r">
        <!-- TODO: Categories -->
        <ul>
          <li>...</li>
        </ul>
      </aside>

      <Nuxt class="w-full lg:w-4/5" />
    </div>
  </main>
</template>

<script>
export default {
  data () {
    return {
      categories: []
    }
  }
}
</script>
