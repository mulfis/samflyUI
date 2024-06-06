<script setup lang="js">
import { Logo } from '@/assets/logo'
import { Facebook, Twitter, Github, Linkedin, Instagram } from '@/components/icons'
</script>

<template>
  <footer class="flex flex-col justify-center items-center w-full py-12">
    <div class="flex m-1">
      <img :src="Logo" width="240" alt="">
    </div>
    <div class="flex justify-evenly">
      <a href="#landing" class="m-2 p-2 font-medium text-gray-500">Product</a>
      <a href="#steps" class="m-2 p-2 font-medium text-gray-500">Steps</a>
      <a href="#features" class="m-2 p-2 font-medium text-gray-500">Features</a>
      <a href="#statistics" class="m-2 p-2 font-medium text-gray-500">Achievements</a>
      <a href="#testimonials" class="m-2 p-2 font-medium text-gray-500">Testimonials</a>
      <a href="#joining" class="m-2 p-2 font-medium text-gray-500">Joining</a>
    </div>
    <div class="flex justify-evenly">
      <a class="mx-2" href="">
        <Facebook fill="#14b8a6" width="24" height="24" />
      </a>
      <a class="mx-2" href="">
        <Twitter fill="#14b8a6" width="24" height="24" />
      </a>
      <a class="mx-2" href="">
        <Github class="fill-teal-500" width="24" height="24" />
      </a>
      <a class="mx-2" href="">
        <Linkedin fill="#14b8a6" width="24" height="24" />
      </a>
      <a class="mx-2" href="">
        <Instagram fill="#14b8a6" width="24" height="24" />
      </a>
    </div>
    <div class="pt-4">
      <p class="font-normal text-gray-500">@2024. Mulfis UI Library. Allrights reserved.</p>
    </div>
  </footer>
</template>