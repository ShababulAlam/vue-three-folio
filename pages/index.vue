<template>
  <div class="bg-stone-500 flex justify-center">
    <div class="container bg-white">
      <Navbar />
      <FolioCard />
      <FolioSkills />
    </div>
  </div>
</template>

<script setup>
import { ref } from "vue";
const counter = ref(0);

const counterUpdate = (type) => {
  if (type === "i") {
    counter.value = counter.value + 1;
  }
  if (type === "d") {
    counter.value = counter.value - 1;
  }
};
</script>

<style lang="scss" scoped></style>
