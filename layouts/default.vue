<template>
  <div>

    <nuxt />

    <!-- This example requires Tailwind CSS v2.0+ -->
    <footer class="bg-white">
      <div class="max-w-7xl mx-auto py-12 px-4 overflow-hidden sm:px-6 lg:px-8">
        <nav class="-mx-5 -my-2 flex flex-wrap justify-center" aria-label="Footer">
          <div class="px-5 py-2">
            <a href="#" class="text-base text-gray-500 hover:text-gray-900">
              About
            </a>
          </div>

          <div class="px-5 py-2">
            <a href="#" class="text-base text-gray-500 hover:text-gray-900">
              Press
            </a>
          </div>

          <div class="px-5 py-2">
            <a href="#" class="text-base text-gray-500 hover:text-gray-900">
              Partners
            </a>
          </div>
        </nav>
        <p class="mt-8 text-center text-base text-gray-400">
          &copy; 2020 emerald-ig.com, Inc. All rights reserved.
        </p>
      </div>
    </footer>

  </div>
</template>

<script>
export default {
  data() {
    return {
      navbarOpen: false
    }
  },
  methods: {
    toggleNavbar() {
      this.navbarOpen = !this.navbarOpen
    }
  }
}
</script>

