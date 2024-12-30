<script setup>
import { onMounted } from "vue";
onMounted(() => {
  setTimeout(() => {
    console.log("Done");
  }, 3000);
});
</script>
<template>
  <div class="w-[400px] h-full flex flex-col justify-center items-center">
    <p class="font-bold">KMS's Tech Blog</p>
    <p class="text-gray-500">with notion</p>
  </div>
</template>
<style></style>
