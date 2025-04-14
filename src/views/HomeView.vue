<script setup>
import Hero from '@/components/HeroSection.vue'
import HomeCards from '@/components/HomeCards.vue'
import JobListings from '@/components/JobListings.vue'
</script>

<template>
  <Hero />
  <HomeCards />
  <JobListings :limit="3" :showButton="true" />
</template>
