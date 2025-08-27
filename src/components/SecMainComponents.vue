<script setup>
import SecMain from "../assets/image-interactive.jpg";
</script>
<template>
  <section class="max-w-[1200px] m-auto py-6 md:py-7 lg:py-8">
    <article
      class="lg:relative flex flex-col items-center lg:flex-row lg:items-start"
    >
      <div>
        <img :src="SecMain" alt="img-fluid" />
      </div>
      <article
        class="bg-white lg:p-16 lg:absolute lg:right-8 lg:bottom-0 lg:w-1/2 text-center lg:text-start pt-4"
      >
        <h2
          class="text-secondary uppercase text-xl sm:text-3xl md:text-4xl lg:text-5xl lg:pb-4"
        >
          The leader in interactive VR
        </h2>
        <p class="text-[#b0b0b0] mt-4 text-sm sm:text-base font-medium">
          Founded in 2011, Loopstudios has been producing world-class virtual
          reality projects for some of the best companies around the globe. Our
          award-winning creations have transformed businesses through digital
          experiences that bind to their brand.
        </p>
      </article>
    </article>
  </section>
</template>

<style lang="scss" scoped></style>
