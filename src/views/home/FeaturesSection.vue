<script setup lang="js">
import { Mail, Growth, People } from '@/components/icons'
import { Feature } from '@/components'
import { ref } from 'vue'

const features = [
  {
    icon: Mail,
    title: 'Share Team Inboxes',
    desc: 'Whether you have a team of 2 or 200, our shared team inboxes keep everyone.',
  },
  {
    icon: Growth,
    title: 'Analytics Dashboard',
    desc: 'Whether you have a team of 2 or 200, our shared team inboxes keep everyone.',
  },
  {
    icon: People,
    title: 'Deliver Instant Answer',
    desc: 'Whether you have a team of 2 or 200, our shared team inboxes keep everyone.',
  },
]

const clickedIndex = ref(1)

const clickHandling = (index) => {
  clickedIndex.value = index
}

</script>

<template>
  <section class="container bg-white flex items-center justify-center pt-52 2xl:pt-[15rem] pb-24" name="features" id="features">
    <div class="flex px-10 text-center">
      <Feature 
        v-for="(feature, index) in features"
        :icon="feature.icon"
        :title="feature.title"
        :desc="feature.desc"
        :type="feature.type"
        :class="{ 'shadow-2xl' : clickedIndex === index }"
        @click="clickHandling(index)"
      />
    </div>
  </section>
</template>