<template>
  <div class="container">
    <div>
      <Logo />
      <h1 class="title ">
        tailwind-yarn-nuxt
      </h1>
      <div class="w-44 h-12 bg-white border-purple-700 border flex items-center justify-center rounded text-purple-700 hover:text-white hover:bg-purple-700 transform hover:shadow-lg hover:-translate-y-3.5 animate-pulse  duration-500 cursor-pointer transition-all ">Documentation</div>
      <div class="links ">
        <a href="https://nuxtjs.org/" target="_blank" rel="noopener noreferrer" class="button--green">
          Documentation
        </a>
        <a href="https://github.com/nuxt/nuxt.js" target="_blank" rel="noopener noreferrer" class="button--grey bg-grey-300">
          GitHub
        </a>
        <div class="btn rounded-r-2xl">123
          <span class="hover:text-yellow-500 transition-all duration-500">456</span>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style lang='postcss'>
.btn {
  @apply cursor-pointer w-28 h-24 bg-purple-700 border-gray-900 flex-row items-center flex justify-center text-white;
}

.container {
  margin: 0 auto;
  min-height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
}

.title {
  font-family: "Quicksand", "Source Sans Pro", -apple-system, BlinkMacSystemFont,
    "Segoe UI", Roboto, "Helvetica Neue", Arial, sans-serif;
  display: block;
  font-weight: 300;
  font-size: 100px;
  color: #35495e;
  letter-spacing: 1px;
}

.subtitle {
  font-weight: 300;
  font-size: 42px;
  color: #526488;
  word-spacing: 5px;
  padding-bottom: 15px;
}

.links {
  padding-top: 15px;
}
</style>
