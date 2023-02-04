<template>
  <section class="hero">
   <div class="container">
      <h1 class="title">Nice to meet you! I'm Jorge Mejia.</h1>
      <p class="subtitle">Based in St. Louis MO, I am a frontend developer. Passionate about building projects and learning about new tech.</p>
      <a class="link" href="#">Contact Me</a>
      <hr>
   </div>
  </section>
</template>

<script>
export default {

}
</script>

<style>
.hero {
   padding: 100px 0;
}
.container {
   width: 100%;
   max-width: 90%;
   margin: 0 auto;
}
.title {
   font-size: 3rem;
   color: white;
   text-align: center;
}
.subtitle {
   color: #ececec;
   line-height: 1.7;
   margin: 15px 0;
   text-align: center;
}
.link {
   font-size: 1.25rem;
   color: white;
   display: block;
   text-align: center;
   margin-bottom: 100px;
}
</style>