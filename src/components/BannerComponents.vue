<script setup>
import Hero from "../assets/image-hero.jpg";
</script>
<template>
  <section>
    <div class="relative">
      <img :src="Hero" alt="Hero Image" class="w-full h-auto object-cover" />
      <div class="absolute inset-0 bg-black opacity-40"></div>
      <div
        class="absolute inset-0 flex justify-center items-center md:justify-start md:max-w-[1200px] md:m-auto md:px-8"
      >
        <div
          class="border-2 border-white sm:p-8 lg:p-9 w-2/5 mt-8 md:mt-20 lg:mt-30 xl:mt-36"
        >
          <h1
            class="text-white text-secondary uppercase text-xl sm:text-3xl md:text-4xl lg:text-6xl text-center md:text-start"
          >
            Immersive experiences that deliver
          </h1>
        </div>
      </div>
    </div>
  </section>
</template>

<style lang="scss" scoped></style>
