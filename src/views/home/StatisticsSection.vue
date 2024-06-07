<script setup lang="js">
import { SamSquare } from '@/assets/img'
import { Statistic } from '@/components'

const statistics = [
  {
    data: '340+',
    title: 'Successful Projects',
    desc: 'Lorem ipsum dolor sit amet, consectetur adipisicing elit.',
  },
  {
    data: '$10m',
    title: 'Annual Percentage Rate',
    desc: 'Lorem ipsum dolor sit amet, consectetur adipisicing elit.',
  },
  {
    data: '2.8k+',
    title: 'Clients Worldwide',
    desc: 'Lorem ipsum dolor sit amet, consectetur adipisicing elit.',
  },
  {
    data: '7000+',
    title: 'Daily Visits',
    desc: 'Lorem ipsum dolor sit amet, consectetur adipisicing elit.',
  },
]
</script>

<template>
  <section class="container bg-white flex items-center justify-center pt-36 2xl:pt-[15rem]" name="statistics" id="statistics">
    <div class="flex justify-between">
      <div class="flex flex-col m-auto items-center justify-center w-1/2">
        <div class="mb-8">
          <h1 class="font-bold text-3xl text-teal-950">Boost your workflow with SamflyUI</h1>
          <p class="font-normal text-gray-500">Lorem ipsum dolor, sit amet consectetur adipisicing elit. Magnam accusamus iste possimus qui.</p>
        </div>
        <div class="grid grid-cols-2 grid-rows-2 gap-6">
          <Statistic
            v-for="statistic in statistics"
            :data="statistic.data"
            :title="statistic.title"
            :desc="statistic.desc"
          />
        </div>
      </div>
      <div class="flex w-1/2 justify-end items-center">
        <img class="w-[75%] rounded-xl" :src="SamSquare" alt="Sam Square">
      </div>
    </div>
  </section>
</template>