<template>
   <section class="projects">
      <div class="container">
         <div class="header-container">
            <h2 class="title">Projects</h2>
            <a href="#" class="link">Contact Me</a>
         </div>
         <div class="projects">

            <div class="project">
               <img class="project-image" src="../assets/image-1.png" alt="project 1">
               <div class="project-title">Design Project</div>
               <div class="project-details">HTML   CSS</div>
               <div class="project-links">
                  <a href="#" class="project-link">View Project</a>
                  <a href="#" class="project-link">View Code</a>
               </div>
            </div>

            <div class="project">
               <img class="project-image" src="../assets/image-1.png" alt="project 1">
               <div class="project-title">Design Project</div>
               <div class="project-details">HTML   CSS</div>
               <div class="project-links">
                  <a href="#" class="project-link">View Project</a>
                  <a href="#" class="project-link">View Code</a>
               </div>
            </div>

         </div>
      </div>
   </section>
</template>


<script>

</script>

<style scoped>
.projects {
   padding: 2em 0;
}
.project {
   margin-bottom: 50px;
}
.header-container {
   display: flex;
   justify-content: space-between;
   align-items: center;
   margin-bottom: 1em;
}
.title {
   font-size: 2.5rem;
   color: white;
}
.link {
   font-size: 1.125rem;
   letter-spacing: 1px;
   color: white;
   text-decoration: none;
   border-bottom: solid aquamarine 2px;
   text-transform: uppercase;
}
.project-image {
   margin-bottom: 20px;
   display: block;
   width: 100%;
}
.project-title {
   color: white;
   text-transform: uppercase;
   font-size: 1.5rem;
   margin-bottom: 20px;
}
.project-details {
   text-transform: uppercase;
   color: rgb(206, 205, 205);
   margin-bottom: 20px;
}
.project-links {
   display: flex;
   justify-content: space-between;
}
.project-link {
   color: white;
   border-bottom: solid aquamarine 2px;
   text-transform: uppercase;
   text-decoration: none;
}
</style>