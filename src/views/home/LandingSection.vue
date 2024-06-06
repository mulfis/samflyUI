<script setup lang="js">
import { Fire } from '@/components/icons'
import { ButtonPrimary, ButtonPhone } from '@/components/buttons'
import { Sam } from '@/assets/img'
</script>

<template>
  <section class="bg-white flex m-auto justify-around h-full pt-28 2xl:pt-[10rem]" name="landing" id="landing">
    <div class="m-auto mr-10 pr-10 w-1/2">
      <div class="p-2 flex">
        <Fire class="mr-2" fill="#14b8a6" width="25" height="25" />
        <p class="text-lg 2xl:text-3xl font-medium text-teal-700">Super Trendies Tailwind Template</p>
      </div>
      <div class="p-2">
        <h1 class="font-bold text-5xl 2xl:text-7xl text-teal-950">Text your website to the next level with <span class="text-teal-500">Samfly</span><span class="text-teal-600">UI</span></h1>
      </div>
      <div class="p-2 py-4">
        <p class="text-gray-900 2xl:text-2xl">Save hundreds of hours trying to create and develop a dashboard from scratch. The fastest, most responsive & trendiest dashboard is here. Seriously.</p>
      </div>
      <div class="flex p-2">
        <ButtonPrimary text="Get Started Now" type="solid"/>
        <ButtonPhone text="Book a Free Call" type="none" />
      </div>
    </div>
    <div class="justify-end flex m-auto pl-10 w-1/2">
      <img :src="Sam" alt="Sam" class="h-[440px] 2xl:h-[660px] rounded-xl">
    </div>
  </section>
</template>