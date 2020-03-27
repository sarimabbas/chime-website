<template>
  <div>
    <Intro />
    <Areas />
  </div>
</template>

<script>
import Intro from '../components/Intro/Intro'
import Areas from '../components/Areas/Areas'
export default {
  components: {
    Intro,
    Areas
  }
}
</script>

<style>
/* Sample `apply` at-rules with Tailwind CSS
.container {
  @apply min-h-screen flex justify-center items-center text-center mx-auto;
}
*/
</style>
