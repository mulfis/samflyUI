<script setup lang="js">
import { ButtonPrimary } from '@/components/buttons'
</script>

<template>
  <section class="container bg-white flex items-center justify-center pt-32 2xl:pt-[15rem] w-full" name="joining" id="joining">
    <div class="flex justify-between w-full">
      <div>
        <p class="font-bold text-3xl text-teal-950">Save time with <span class="text-teal-500">Samfly</span><span class="text-teal-600">UI</span>.</p>
        <p class="text-3xl text-teal-950">Turn your visitors into clients</p>
      </div>
      <div class="my-auto">
        <ButtonPrimary text="Try Demo" type="outline" />
        <ButtonPrimary text="Get Started Now" />
      </div>
    </div>
  </section>
</template>