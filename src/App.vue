<script setup>
import Narbar from "./components/Narbar.vue";
import Hero from "./components/Hero.vue";
import HomeCards from "./components/HomeCards.vue";
import JobListings from "./components/JobListings.vue";
</script>

<template>
  <Narbar />
  <Hero />
  <HomeCards />
  <JobListings :limit="3" :showButton="true" />
</template>
