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
  color: #1E3240;
}

.content {
  max-width: 1110px;
  margin: 0 auto;
}

.btn {
  padding: 18px 24px;
  font-size: 14px;
  font-weight: 400;
  border-radius: 0;
  border: none;
  cursor: pointer;
  font-family: 'Mulish', sans-serif;

  &-primary {
    background-color: #1E3240;
    color: #fff;
  }

  &-secondary {
    background-color: #AFD4E2;
    border: 1px solid #1E3240;
    color: #1E3240;
  }
}
</style>
