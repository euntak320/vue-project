<script setup lang="ts">
import Header from '@/components/Header.vue';
import Contact from '@/components/Contact.vue';
import Footer from '@/components/Footer.vue';
import Skill from '@/components/skill.vue';
import Skip from '@/components/Skip.vue';
import Intro from '@/components/intro.vue';
import Port from '@/components/Port.vue';
import Site from '@/components/Site.vue';
</script>

<template>
  <Skip />
  <Header />
  <main id ="main" role="main">
    <Intro />
    <Skill />
    <Port />
    <Site />
    <Contact />
  </main>
  <Footer />
</template>
