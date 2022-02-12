<script setup>
import Header from "./components/Header.vue";
import About from "./components/About.vue";
import Projects from "./components/Projects.vue";
import Testimonial from "./components/Testimonial.vue";
import Contact from "./components/Contact.vue";
import Footer from "./components/Footer.vue";
</script>

<template>
  <Header />
  <About />
  <Projects />
  <Testimonial />
  <Contact />
  <Footer />
</template>

<style lang="scss">
@import url('https://fonts.googleapis.com/css2?family=Mulish:wght@300;400;700&display=swap');

* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  font-family: 'Mulish', sans-serif;
}
</style>
