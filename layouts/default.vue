<script>
import Navbar from '../components/Navbar/Navbar'
export default {
  components: {
    Navbar
  }
}
</script>

<template>
  <div>
    <header class="sticky top-0">
      <Navbar />
    </header>
    <main>
      <nuxt />
    </main>
    <footer>Footer</footer>
  </div>
</template>

<style>
</style>
