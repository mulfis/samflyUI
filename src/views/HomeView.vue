<script setup lang="js">
import { Header, Footer } from '@/components'
import { LandingSection, StepsSection, FeaturesSection, StatisticsSection, TestimonialsSection, JoiningSection } from '@/views/home'
</script>

<template>
  <Header />
  <main class="flex flex-col px-10 md:px-36 2xl:px-56 pb-16 h-auto w-full m-auto">
    <LandingSection />
    <StepsSection />
    <FeaturesSection />
    <StatisticsSection />
    <TestimonialsSection />
    <JoiningSection/>
  </main>
  <Footer />
</template>
