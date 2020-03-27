<template>
  <section class="h-screen">
    <div class="mt-10 md:mt-0 md:flex sectionFull">
      <!-- text -->
      <div class="mb-10 md:mb-0 md:items-center md:h-full md:flex md:w-1/2">
        <div class="px-6 md:px-6 lg:pl-16 lg:pr-32">
          <h2 class="mb-3 text-2xl font-semibold tracking-wide text-gray-600 uppercase">Chime</h2>
          <h1
            class="mb-6 text-4xl font-semibold leading-tight tracking-tight text-gray-800"
          >Coalition for Health Innovation in Medical Emergencies</h1>
          <p
            class="text-xl"
          >Lorem ipsum dolor sit, amet consectetur adipisicing elit. Ea, autem, dolorum, repellendus dolore quae eaque vitae dolorem nihil minus consectetur blanditiis alias cumque quos asperiores provident? Ea fugiat corrupti sapiente?</p>
        </div>
      </div>
      <!-- image -->
      <div class="md:h-full md:w-1/2 md:block">
        <img
          class="object-cover h-full"
          src="https://images.squarespace-cdn.com/content/v1/55833fc0e4b07d6bd2063c9e/1435245150715-GZM0ZMYMRTU7D7KOKY1I/ke17ZwdGBToddI8pDm48kLkXF2pIyv_F2eUT9F60jBl7gQa3H78H3Y0txjaiv_0fDoOvxcdMmMKkDsyUqMSsMWxHk725yiiHCCLfrh8O1z4YTzHvnKhyp6Da-NYroOW3ZGjoBKy3azqku80C789l0iyqMbMesKd95J-X4EagrgU9L3Sa3U8cogeb0tjXbfawd0urKshkc5MgdBeJmALQKw/IMG_2287.JPG?format=2500w"
          alt
        />
      </div>
    </div>
  </section>
</template>

<script>
export default {
  components: {}
}
</script>

<style>
/* Sample `apply` at-rules with Tailwind CSS
.container {
  @apply min-h-screen flex justify-center items-center text-center mx-auto;
}
*/

.sectionFull {
  height: calc(100vh - 4rem);
}
</style>
