<script setup>
import Card5Image from "../assets/image-from-above.jpg";
</script>
<template>
  <div class="relative cursor-pointer">
    <img :src="Card5Image" alt="Card 5 Image" class="img-fluid" />
    <div
      class="absolute inset-0 bg-gradient-to-t from-black/70 to-transparent"
    ></div>
    <div class="absolute bottom-8 left-8">
      <h3
        class="text-white text-primary text-xl md:text-2xl lg:text-3xl uppercase w-3/4"
      >
        From up above VR
      </h3>
    </div>
  </div>
</template>

<style lang="scss" scoped></style>
