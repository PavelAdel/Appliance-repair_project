<template>
   <div class="container" id="top">
      <div class="v-nav-bar">
         <nav class="navbar navbar-expand-lg navbar-light">
            <a class="navbar-brand" href="#">
               <img class="v-navbar__logo" src="../assets/images/ar-logo.png" alt="">
            </a>

            <button
               class="navbar-toggler"
               type="button"
               data-bs-toggle="collapse"
               data-bs-target="#navbarNav"
               aria-controls="navbarNav"
               aria-expanded="false"
               aria-label="Toggle navigation"
            >
               <span class="navbar-toggler-icon"></span>
            </button>

            <div class="collapse navbar-collapse" id="navbarNav">
               <ul class="navbar-nav ms-auto">
                  <li class="nav-item">
                     <a class="nav-link" href="#service">Service</a>
                  </li>
                  <li class="nav-item">
                     <a class="nav-link" href="#work">We work with</a>
                  </li>
                  <li class="nav-item">
                     <a class="nav-link" href="#numbers">Results</a>
                  </li>
                  <li class="nav-item">
                     <a class="nav-link" href="#contact">Contact</a>
                  </li>
               </ul>
            </div>
         </nav>
      </div>
   </div>
</template>

<script>

export default {
   name: 'v-nav-bar',
   data() {
      return {

      }
   }
}
</script>

<style>
.v-navbar__logo {
   width: 150px;
}
.nav-item {
   text-transform: uppercase;
   font-size: 16px;
   font-weight: 600;
   margin-left: 30px;
}
.navbar-nav .nav-item .nav-link:hover {
    color: rgb(175, 15, 15);
}

</style>
