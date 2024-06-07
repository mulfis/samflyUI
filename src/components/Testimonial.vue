<script setup lang="js">
defineProps({
  desc: String,
  name: String,
  job: String,
  image: String,
})
</script>

<template>
  <article class="flex flex-col items-center justify-center text-center p-6 m-2 bg-teal-100 rounded-xl">
    <div class="my-5">
      <p class="font-semibold">
        {{ desc }}
      </p>
    </div>
    <div class="flex flex-col items-center mt-2">
      <img 
        class="h-10 w-10 rounded-full m-2" 
        :src="image" 
        alt="Testimoni's Profile Photo"
      >
      <p class="font-bold text-teal-950 text-lg">
        {{ name }}
      </p>
      <p class="font-semibold text-sm text-gray-500">
        {{ job }}
      </p>
    </div>
  </article>
</template>