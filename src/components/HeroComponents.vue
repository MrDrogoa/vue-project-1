<script setup>
import NavbarComponents from "./NavbarComponents.vue";
import BannerComponents from "./BannerComponents.vue";
</script>
<template>
  <section class="pb-[30%] sm:pb-[33%] md:pb-[35%] lg:pb-[38%] xl:pb-[43%]">
    <div class="relative">
      <div class="z-10 relative">
        <NavbarComponents />
      </div>
      <div class="absolute inset-0 z-0">
        <BannerComponents />
      </div>
    </div>
  </section>
</template>

<style lang="scss" scoped></style>
