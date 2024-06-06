<script setup lang="js">
import { SamSquare } from '@/assets/img'
</script>

<template>
  <section class="container bg-white flex items-center justify-center pt-36 2xl:pt-[15rem]" name="statistics" id="statistics">
    <article class="flex justify-between">
      <div class="flex flex-col m-auto items-center justify-center w-1/2">
        <div class="mb-8">
          <h1 class="font-bold text-3xl text-teal-950">Boost your workflow with SamflyUI</h1>
          <p class="font-normal text-gray-500">Lorem ipsum dolor, sit amet consectetur adipisicing elit. Magnam accusamus iste possimus qui.</p>
        </div>
        <div class="grid grid-cols-2 grid-rows-2 gap-6">
          <div>
            <h2 class="font-bold text-4xl text-teal-950">340+</h2>
            <h3 class="font-semibold text-lg text-teal-800">Successful Projects</h3>
            <p class="font-normal text-gray-500">Lorem ipsum dolor sit amet, consectetur adipisicing elit.</p>
          </div>
          <div>
            <h2 class="font-bold text-4xl text-teal-950">$10m</h2>
            <h3 class="font-semibold text-lg text-teal-800">Annual Percentage Rate</h3>
            <p class="font-normal text-gray-500">Lorem ipsum dolor sit amet consectetur adipisicing elit.
            </p>
          </div>
          <div>
            <h2 class="font-bold text-4xl text-teal-950">2.8k+</h2>
            <h3 class="font-semibold text-lg text-teal-800">Clients Worldwide</h3>
            <p class="font-normal text-gray-500">Lorem ipsum dolor sit amet consectetur adipisicing elit.</p>
          </div>
          <div>
            <h2 class="font-bold text-4xl text-teal-950">7000+</h2>
            <h3 class="font-semibold text-lg text-teal-800">Daily Visits</h3>
            <p class="font-normal text-gray-500">Lorem ipsum dolor sit, amet consectetur adipisicing elit.</p>
          </div>
        </div>
      </div>
      <div class="flex w-1/2 justify-end items-center">
        <img class="w-[75%] rounded-xl" :src="SamSquare" alt="Sam Square">
      </div>
    </article>
  </section>
</template>