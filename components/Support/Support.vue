<script>
import Card from '../Card/Card'
export default {
  components: {
    Card
  }
}
</script>

<template>
  <section id="support" class="px-6 py-16 md:py-0 lg:px-32">
    <div class="flex flex-wrap items-center h-full text-center md:h-screen">
      <div>
        <!-- text -->
        <div class="flex flex-wrap justify-center pb-16">
          <h1
            class="pb-4 text-4xl font-semibold leading-tight tracking-tight text-gray-800"
          >Chime in with your support</h1>
          <p
            class="text-xl md:px-32 lg:px-40"
          >Lorem ipsum dolor sit, amet consectetur adipisicing elit. Ea, autem, dolorum, repellendus dolore quae eaque vitae dolorem nihil minus consectetur blanditiis alias cumque quos asperiores provident? Ea fugiat corrupti sapiente?</p>
        </div>
        <!-- cards -->
        <div class="card-grid">
          <div>
            <h2 class="pb-2 text-2xl font-semibold">
              Make a
              <br />financial contribution
            </h2>
            <p
              class="pb-4"
            >Lorem ipsum, dolor sit amet consectetur adipisicing elit. Veniam voluptatibus nihil excepturi illo nobis enim a explicabo modi vitae perspiciatis molestias sint molestiae nulla, alias iure quaerat! Sit, perspiciatis ex.</p>
            <button
              class="px-3 py-2 text-sm font-medium leading-5 text-white bg-gray-900 rounded-md hover:bg-gray-700"
            >Donate</button>
          </div>
          <div>
            <h2 class="pb-2 text-2xl font-semibold">
              Donate personal
              <br />protective equipment
            </h2>
            <p
              class="pb-4"
            >Lorem ipsum, dolor sit amet consectetur adipisicing elit. Veniam voluptatibus nihil excepturi illo nobis enim a explicabo modi vitae perspiciatis molestias sint molestiae nulla, alias iure quaerat! Sit, perspiciatis ex.</p>
            <button
              class="px-3 py-2 text-sm font-medium leading-5 text-white bg-gray-900 rounded-md hover:bg-gray-700"
            >Donate</button>
          </div>
          <div>
            <h2 class="pb-2 text-2xl font-semibold">
              Share an
              <br />innovative idea
            </h2>
            <p
              class="pb-4"
            >Lorem ipsum, dolor sit amet consectetur adipisicing elit. Veniam voluptatibus nihil excepturi illo nobis enim a explicabo modi vitae perspiciatis molestias sint molestiae nulla, alias iure quaerat! Sit, perspiciatis ex.</p>
            <a
              class="px-3 py-2 text-sm font-medium leading-5 text-white transition duration-150 ease-in-out bg-gray-900 rounded-md focus:outline-none focus:text-white focus:bg-gray-700"
            >Research</a>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>



<style scoped>
.card-grid {
  gap: 4rem;
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(15rem, 1.5fr));
}
</style>