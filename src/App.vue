<template>
   <main>
      <Header></Header>
      <Hero></Hero>
      <hr class="line">
      <Skills></Skills>
      <hr class="line">
      <Projects></Projects>
      <Contact></Contact>
      <Footer></Footer>
   </main>
</template>

<script>
import Header from './components/Header.vue'
import Hero from './components/Hero.vue'
import Skills from './components/Skills.vue'
import Projects from './components/Projects.vue'
import Contact from './components/Contact.vue'
import Footer from './components/Footer.vue'
export default {
   components: {
      Header,
      Hero,
      Skills,
      Projects,
      Contact,
      Footer
   }
}
</script>

<style>
.line {
   width: 100%;
   max-width: 90%;
   margin: 0 auto;
}
.container {
   width: 100%;
   max-width: 95%;
   margin: 0 auto;
}

@media screen and (min-width: 760px) {
   .container {
      max-width: 90%;
   }
}
</style>
