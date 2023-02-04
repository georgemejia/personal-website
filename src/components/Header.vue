<template>
  <header class="header">
      <div class="container">
         <a class="brand" href="#">jorgemejia</a>
         <nav class="nav">
            <a class="nav-link" href="#">twitter</a>
            <a class="nav-link" href="#">linkedin</a>
         </nav>
      </div>
  </header>
</template>

<script>
export default {

}
</script>

<style>
.header {
   padding: 2em 0;
}
.container {
   width: 100%;
   max-width: 90%;
   margin: 0 auto;
}
.brand {
   color: white;
   font-size: 1.25rem;
   text-decoration: none;
   display: block;
   text-align: center;
   margin-bottom: 20px;
}
.nav {
   text-align: center;
}
.nav-link {
   color: white;
   margin: 0 8px;
}
</style>