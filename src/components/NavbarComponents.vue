<script setup>
import ListComponents from "./ListComponents.vue";
import LogoComponents from "./LogoComponents.vue";
</script>
<template>
  <section class="max-w-[1200px] m-auto py-6 md:py-7 lg:py-8 z-10">
    <article class="flex justify-between items-center px-7 md:px-8">
      <div>
        <LogoComponents />
      </div>
      <div class="text-white font-medium">
        <ListComponents />
      </div>
    </article>
  </section>
</template>

<style lang="scss" scoped></style>
