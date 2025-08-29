<script setup>
import Card6Image from "../assets/image-pocket-borealis.jpg";
</script>
<template>
  <div class="relative cursor-pointer">
    <img :src="Card6Image" alt="Card 6 Image" class="img-fluid" />
    <div
      class="absolute inset-0 bg-gradient-to-t from-black/70 to-transparent"
    ></div>
    <div class="absolute bottom-8 left-8">
      <h3
        class="text-white text-primary text-xl md:text-2xl lg:text-3xl uppercase w-3/4"
      >
        Pocket borealis
      </h3>
    </div>
  </div>
</template>

<style lang="scss" scoped></style>
