<script setup>
import { RouterLink, RouterView } from 'vue-router'
import Navbar from './components/Navbar.vue';
import Hero from './components/Hero.vue';
import About from './components/About.vue';
import Services from './components/Services.vue';
import Technologies from './components/Technologies.vue';
import Contact from './components/Contact.vue';

</script>

<template>
  <div style="backgroundImage:url('./src/assets/back.svg')" class="h-auto w-full bg-contain bg-no-repeat">
    <Navbar/> 
    <Hero/>
    <About/>
    <Services/>
    <Technologies/>
    <Contact/>
    <RouterView />
  </div>
</template>

