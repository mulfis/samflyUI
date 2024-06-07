<script setup lang="js">
import { Logo } from '@/assets/logo'
import { Facebook, Twitter, Github, Linkedin, Instagram } from '@/components/icons'
import { Navigation, Icons } from '@/components'

const navigations = [
  {
    loc: '#landing',
    name: 'Product',
  },
  {
    loc: '#steps',
    name: 'Steps',
  },
  {
    loc: '#features',
    name: 'Features',
  },
  {
    loc: '#statistics',
    name: 'Achievement',
  },
  {
    loc: '#testimonials',
    name: 'Testimonials',
  },
  {
    loc: '#joining',
    name: 'Joining',
  },
]

const icons = [
  {
    icon: Facebook,
    link: '',
  },
  {
    icon: Twitter,
    link: '',
  },
  {
    icon: Github,
    link: '',
  },
  {
    icon: Linkedin,
    link: '',
  },
  {
    icon: Instagram,
    link: '',
  },
]

</script>

<template>
  <footer class="flex flex-col justify-center items-center w-full py-12">
    <div class="flex m-1">
      <img :src="Logo" width="240" alt="">
    </div>
    <div class="flex justify-evenly">
      <Navigation
        v-for="navigate in navigations"
        :loc="navigate.loc"
        :name="navigate.name"
      />
    </div>
    <div class="flex justify-evenly">
      <Icons 
        v-for="icon in icons"
        :icon="icon.icon"
        :link="icon.link"
      />
    </div>
    <div class="pt-4">
      <p class="font-normal text-gray-500">@2024. Mulfis UI Library. Allrights reserved.</p>
    </div>
  </footer>
</template>