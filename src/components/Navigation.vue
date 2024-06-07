<script setup lang="js">
defineProps({
  loc: String,
  name: String,
})
</script>

<template>
  <a 
  :href="loc" 
  class="m-2 p-2 font-medium text-gray-500">
    {{ name }}
  </a>
</template>