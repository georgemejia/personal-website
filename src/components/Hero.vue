<template>
  <section class="hero">
   <div class="container">
      <h1 class="title">Nice to meet you! I'm <span class="name">Jorge Mejia</span>.</h1>
      <p class="subtitle">Based in St. Louis MO, I am a frontend developer. Passionate about building projects and learning about new tech.</p>
      <div class="link-container">
         <a class="link" href="#">Contact Me</a>
      </div>
   </div>
  </section>
</template>

<style scoped>
.hero {
   padding: 50px 0;
}
.name {
  border-bottom: solid aquamarine 2px;
}
.title {
   font-size: 2.5rem;
   color: white;
   text-align: center;
}
.subtitle {
   color: #ececec;
   line-height: 1.7;
   margin: 25px 0;
   text-align: center;
}
.link-container {
   display: flex;
   justify-content: center;
}
.link {
   font-size: 1.125rem;
   color: white;
   text-decoration: none;
   border-bottom: solid aquamarine 2px;
   text-transform: uppercase;
   letter-spacing: 1px;
}
</style>