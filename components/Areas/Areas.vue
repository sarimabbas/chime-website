<script>
import Card from '../Card/Card'
export default {
  components: {
    Card
  }
}
</script>

<template>
  <section
    id="research"
    class="flex flex-wrap items-center px-6 py-16 bg-gray-100 sectionFull md:px-6 lg:px-16 lg:px-32"
  >
    <div>
      <!-- text -->
      <div class="flex flex-wrap justify-center pb-16">
        <h1
          class="pb-4 text-4xl font-semibold leading-tight tracking-tight text-gray-800"
        >Areas of research</h1>
        <p
          class="text-xl md:px-32 lg:px-40"
        >Lorem ipsum dolor sit, amet consectetur adipisicing elit. Ea, autem, dolorum, repellendus dolore quae eaque vitae dolorem nihil minus consectetur blanditiis alias cumque quos asperiores provident? Ea fugiat corrupti sapiente?</p>
      </div>
      <!-- cards -->
      <div class="card-grid">
        <Card />
        <Card />
        <Card />
        <Card />
      </div>
    </div>
  </section>
</template>



<style scoped>
.card-grid {
  gap: 1.5rem;
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(15rem, 1.5fr));
}
</style>