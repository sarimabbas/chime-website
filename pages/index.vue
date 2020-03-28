<template>
  <div>
    <Intro />
    <Areas />
    <Support />
  </div>
</template>

<script>
import Intro from '../components/Intro/Intro'
import Areas from '../components/Areas/Areas'
import Support from '../components/Support/Support'
export default {
  components: {
    Intro,
    Areas,
    Support
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
