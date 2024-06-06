<script setup lang="js">
import { Phone } from '@/components/icons'

defineProps({
  text: String,
  type: {
    default: 'none'
  }
})
</script>

<template>
  <button 
    v-if="type == 'solid'" 
    class="flex m-1 py-2 px-4 bg-teal-500 text-white rounded-xl font-normal hover:bg-teal-700 border border-teal-500 hover:border-teal-700 transition-colors">
    <Phone class="mr-2 my-1 hover:fill-teal-500 fill-white" width="20" height="20"/>
    {{ text }}
  </button>
  <button
    v-else-if="type == 'outline'"
    class="flex m-1 py-2 px-4 font-normal bg-white hover:bg-teal-500 border text-teal-500 hover:text-white border-teal-500 rounded-xl transition-all">
    <Phone class="mr-2 my-1 fill-teal-500 hover:fill-white" width="20" height="20"/>
    {{ text }}
  </button>
  <button
    v-else
    class="flex m-1 py-2 px-4 font-normal bg-white text-gray-600">
    <Phone class="mr-2 my-1 fill-gray-600" width="20" height="20"/>
    {{ text }}
  </button>
</template>