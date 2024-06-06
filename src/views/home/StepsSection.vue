<script setup lang="js">
import { ChevronRight } from '@/components/icons'
</script>

<template>
  <section class="container bg-white flex m-auto pt-52 2xl:pt-[15rem]" name="steps" id="steps">
    <article class="m-auto">
      <h1 class="p-3 font-bold text-teal-950 text-4xl  text-center">How SamflyUI Works?</h1>
      <p class="font-medium text-gray-500 text-center">Tellus rutrum tellus pellentesque eu tincidunt tortor condimentum.</p>
      <div class="mt-16 flex">
        <div class="flex px-3">
          <div class="flex items-center justify-center w-10 h-10 rounded-full text-white bg-teal-500">
            <p class="flex-none font-medium">1</p>
          </div>
          <div class="flex-1 pl-3">
            <h2 class="font-bold text-teal-950">Create your Account</h2>
            <p class="font-medium text-gray-500">Condimentum vit pellemsque habitant morbi at molestie.</p>
          </div>
        </div>
        <div class="flex m-auto px-3">
          <ChevronRight class="fill-gray-700" width="20" height="20" />
        </div>
        <div class="flex px-3">
          <div class="flex items-center justify-center w-10 h-10 rounded-full text-teal-500 border-2 border-teal-500">
            <p class="flex-none font-medium">2</p>
          </div>
          <div class="flex-1 pl-3">
            <h2 class="font-bold text-teal-950">Setup your Account</h2>
            <p class="font-medium text-gray-500">Condimentum vit pellemsque habitant morbi at molestie.</p>
          </div>
        </div>
        <div class="flex m-auto px-3">
          <ChevronRight class="fill-gray-700" width="20" height="20" />
        </div>
        <div class="flex px-3">
          <div class="flex items-center justify-center w-10 h-10 rounded-full text-teal-500 border-2 border-teal-500">
            <p class="flex-none font-medium">3</p>
          </div>
          <div class="flex-1 pl-3">
            <h2 class="font-bold text-teal-950">Start creating with Samfly</h2>
            <p class="font-medium text-gray-500">Condimentum vit pellemsque habitant morbi at molestie.</p>
          </div>
        </div>
      </div>
    </article>
  </section>
</template>