<script setup>
import NavBar from '@/components/NavBar.vue';
import Hero from '@/components/Hero.vue';
import HomeCards from '@/components/HomeCards.vue';
import JobsListings from '@/components/JobsListings.vue';

</script>

<template>
  <h1 class="text-2xl">Vue Jobs</h1>
  <NavBar />
  <Hero />
  <HomeCards />
  <JobsListings :limit="3" :showButton="true"/>
</template>