<script setup lang="js">
defineProps({
  icon: Object,
  title: String,
  desc: String,
})

</script>

<template>
  <article 
    class="p-6 rounded-xl hover:cursor-pointer">
    <div class="flex m-auto justify-center items-center w-14 h-14 bg-teal-500 rounded-xl">
      <component :is="icon" class="fill-white" width="25" height="25" />                    
    </div>
    <h1 class="font-bold text-xl text-teal-950 p-2 mt-2">
      {{ title }}
    </h1>
    <p class="font-normal text-gray-500">
      {{ desc }}
    </p>
  </article>
  
</template>