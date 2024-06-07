<script setup lang="js">
defineProps({
  icon: Object,
  link: String,
})
</script>

<template>
  <a 
  class="mx-2" 
  :href="link">
    <component :is="icon" class="fill-teal-500" width="24" height="24" />
  </a>
</template>