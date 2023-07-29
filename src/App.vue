<template>
  <div>
    <navbar-component></navbar-component>
    <head-component></head-component>
    <br>
    <about-component></about-component>
    <br>
    <gallery-component></gallery-component>
    <br>
    <se-component></se-component>
    <pen-component></pen-component>
    <contact-component></contact-component>
    <footer-component></footer-component>
    
  </div>
</template>

<script setup>
  import 'flowbite/dist/flowbite.js';

  import NavbarComponent from './NavbarComponent.vue';
  import HeadComponent from './HeadComponent.vue';
  import AboutComponent from './AboutComponent.vue';
  import GalleryComponent from './GalleryComponent.vue';
  import SeComponent from './SeComponent.vue';
  import PenComponent from './PenComponent.vue';
  import ContactComponent from './ContactComponent.vue'
  import FooterComponent from './FooterComponent.vue';
  
  
</script>