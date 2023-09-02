<script setup lang="ts">
useHead({
  title: 'Iris Enthoven',
  meta: [
    { name: 'description', content: 'Iris Enthoven Podcast-landingspaginawebsite.' },
  ],
  link: [
    { rel: 'icon', type: 'image/png', href: '/logo.png' }
  ],
})
</script>
<template>
    <div>
        <SectionsHomeHeroSection/>
        <SectionsHomeLatestPodcast/>
        <SectionsHomePopularPodcasts/>
        <SectionsAboutPodux/>
        <SectionsWhyUs/>
        <SectionsCallToAction/>
    </div>
</template>