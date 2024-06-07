<script setup lang="js">
import { Trailblazer, Clara } from '@/assets/img'
import { Testimonial } from '@/components'

const testimonials = [
  {
    name: 'Trailblazer',
    job: 'Main Character',
    image: Trailblazer,
    desc: '“A must needed kit for every single software arhitect. It makes your coding life easier and your final product will be blooming."',
  },
  {
    name: 'Clara',
    job: 'Belobog SSR Character',
    image: Clara,
    desc: '“A must needed kit for every single software arhitect. It makes your coding life easier and your final product will be blooming."',
  },
]

</script>

<template>
  <section class="container bg-white flex flex-col items-center justify-center pt-28 2xl:pt-[15rem] px-10 w-full" name="testimonials" id="testimonials">
    <div class="m-auto pb-10 text-center h-auto w-[60%]">
      <h1 class="font-bold text-teal-950 text-3xl mb-2">Customer Testimonials</h1>
      <p class="font-medium text-gray-500">Anim aute id magna aliqua ad ad non deserunt sunt. Qui irure qui lorem cupidatat commodo. Elit sunt amet fugiat veniam occaecat fugiat aliqua.</p>
    </div>
    <div class="grid grid-cols-2 gap-x-5">
      <Testimonial 
        v-for="testimonial in testimonials"
        :desc="testimonial.desc"
        :image="testimonial.image"
        :name="testimonial.name"
        :job="testimonial.job"
      />
    </div>
  </section>
</template>