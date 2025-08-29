<script setup>
import Card1Components from "./Card1Components.vue";
import Card2Components from "./Card2Components.vue";
import Card3Components from "./Card3Components.vue";
import Card4Components from "./Card4Components.vue";
import Card5Components from "./Card5Components.vue";
import Card6Components from "./Card6Components.vue";
import Card7Components from "./Card7Components.vue";
import Card8Components from "./Card8Components.vue";
import ButtonComponents from "./ButtonComponents.vue";
</script>
<template>
  <section>
    <article class="flex flex-wrap justify-center gap-5 lg:gap-7">
      <div>
        <Card1Components />
      </div>
      <div>
        <Card2Components />
      </div>
      <div>
        <Card3Components />
      </div>
      <div>
        <Card4Components />
      </div>
      <div>
        <Card5Components />
      </div>
      <div>
        <Card6Components />
      </div>
      <div>
        <Card7Components />
      </div>
      <div>
        <Card8Components />
      </div>
    </article>
    <article class="lg:hidden flex justify-center mt-10 lg:mt-14">
      <ButtonComponents />
    </article>
  </section>
</template>

<style lang="scss" scoped></style>
