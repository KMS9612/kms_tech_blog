<script setup>
const navList = ref([
  { to: "/", alt: "mainPage" },
  { to: "/about", alt: "aboutPage" },
  { to: "/list", alt: "listPage" },
]);
</script>
<template>
  <nav>
    <h2>Navigation</h2>
    <ol>
      <li class="text-sm font-bold cursor-pointer" v-for="item in navList">
        <NuxtLink :to="item.to">
          {{ item.alt }}
        </NuxtLink>
      </li>
    </ol>
  </nav>
</template>
