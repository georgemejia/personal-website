<template>
   <section class="contact">
      <div class="container">
         <h2 class="title">Contact</h2>
         <p class="subtitle">I would love to hear about your project and how I could help. Please fill in the form, and I'll get back to you as soon as possible.</p>
         <form class="form">
            <div class="form-row">
               <input class="form-input" type="text" placeholder="Name">
            </div>
            <div class="form-row">
               <input class="form-input" type="text" placeholder="Email">
            </div>
            <div class="form-row">
               <input class="form-input" type="text" placeholder="Message">
            </div>
            <div class="form-row">
               <button class="form-button" type="submit">Send Message</button>
            </div>
         </form>
      </div>
   </section>
</template>

<style scoped>
.contact {
   padding: 50px 0;
   background-color: #272727;
}
.title {
   font-size: 2.5rem;
   color: white;
   margin-bottom: 20px;
   text-align: center;
}
.subtitle {
   color: white;
   margin-bottom: 20px;
   text-align: center;
}
.form-row {
   margin-bottom: 8px;
}
.form-input {
   display: block;
   width: 100%;
   padding: 1em;
   background-color: inherit;
   border: none;
   border-bottom: 1px solid white;
}
.form-input::placeholder {
   color: white;
   font-size: 1rem;
   text-transform: uppercase;
   letter-spacing: 1px;
}
.form-button {
   border: none;
   border-bottom: 1px solid aquamarine;
   background-color: inherit;
   padding: 1em 2em;
   color: white;
   text-transform: uppercase;
   font-size: 1rem;
   letter-spacing: 1px;
}
.form-row:nth-child(4) {
   display: flex;
   justify-content: end;
}
</style>