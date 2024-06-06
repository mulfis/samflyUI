<script setup lang="js">
import { Mail, Growth, People } from '@/components/icons'
</script>

<template>
  <section class="container bg-white flex items-center justify-center pt-52 2xl:pt-[15rem] pb-24" name="features" id="features">
    <article class="flex px-10 text-center">
      <div class="p-4">
        <div class="flex m-auto justify-center items-center w-14 h-14 bg-teal-500 rounded-xl">
          <Mail fill="#ffffff" width="25" height="24" />                          
        </div>
        <h1 class="font-bold text-xl text-teal-950 p-2 mt-2">Share team inboxes</h1>
        <p class="font-normal text-gray-500">Whether you have a team of 2 or 200, our shared team inboxes keep everyone.</p>
      </div>
      <div class="p-4 bg-white shadow-2xl rounded-2xl">
        <div class="flex m-auto justify-center items-center w-14 h-14 bg-teal-500 rounded-xl">
          <Growth fill="#ffffff" width="25" height="24" />
        </div>
        <h1 class="font-bold text-xl text-teal-950 p-2 mt-2">Analytics dashboard</h1>
        <p class="font-normal text-gray-500">Whether you have a team of 2 or 200, our shared team inboxes keep everyone.</p>
      </div>
      <div class="flex flex-col p-4">
        <div class="flex m-auto justify-center items-center w-14 h-14 bg-teal-500 rounded-xl">
          <People fill="#ffffff" width="25" height="24" />              
        </div>
        <h1 class="font-bold text-xl text-teal-950 p-2 mt-2">Deliver instant answer</h1>
        <p class="font-normal text-gray-500">Whether you have a team of 2 or 200, our shared team inboxes keep everyone.</p>
      </div>
    </article>
  </section>
</template>