<script setup>
import Card8Image from "../assets/image-fisheye.jpg";
</script>
<template>
  <div class="relative cursor-pointer">
    <img :src="Card8Image" alt="Card 8 Image" class="img-fluid" />
    <div
      class="absolute inset-0 bg-gradient-to-t from-black/70 to-transparent"
    ></div>
    <div class="absolute bottom-8 left-8">
      <h3
        class="text-white text-primary text-xl md:text-2xl lg:text-3xl uppercase w-3/4"
      >
        Make it fisheye
      </h3>
    </div>
  </div>
</template>

<style lang="scss" scoped></style>
