<script setup lang="js">
defineProps({
  data: String,
  title: String,
  desc: String,
})
</script>

<template>
  <article>
    <h2 class="font-bold text-4xl text-teal-950">
      {{ data }}
    </h2>
    <h3 class="font-semibold text-lg text-teal-800">
      {{ title }}
    </h3>
    <p class="font-normal text-gray-500">
      {{ desc }}
    </p>
  </article>
</template>