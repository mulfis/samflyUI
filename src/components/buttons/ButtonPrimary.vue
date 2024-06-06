<script setup lang="js">
defineProps({
  text: String,
  type: {
    default: 'solid'
  }
})
</script>

<template>
  <button 
    v-if="type == 'solid'" 
    class="m-1 py-2 px-4 bg-teal-500 text-white rounded-xl font-normal hover:bg-teal-700 border border-teal-500 hover:border-teal-700 transition-colors">
    {{ text }}
  </button>
  <button
    v-else-if="type == 'outline'"
    class="m-1 py-2 px-4 font-normal bg-white hover:bg-teal-500 border text-teal-500 hover:text-white border-teal-500 rounded-xl transition-all">
    {{ text }}
  </button>
</template>