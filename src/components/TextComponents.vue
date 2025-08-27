<script setup>
import ButtonComponents from "./ButtonComponents.vue";
</script>
<template>
  <section
    class="max-w-[1200px] m-auto py-6 md:py-7 lg:py-14 px-4 sm:px-6 lg:px-0"
  >
    <div class="flex lg:justify-between justify-center items-center">
      <article>
        <h2
          class="text-secondary uppercase text-xl sm:text-3xl md:text-4xl lg:text-5xl lg:pb-4"
        >
          Our creations
        </h2>
      </article>
      <article>
        <ButtonComponents class="hidden lg:block" />
      </article>
    </div>
  </section>
</template>

<style lang="scss" scoped></style>
