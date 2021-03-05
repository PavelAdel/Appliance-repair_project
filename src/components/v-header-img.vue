<template>
   <div class="v-header-img">
      <div
         id="carouselExampleFade"
         class="carousel slide carousel-fade"
         data-bs-ride="carousel"
      >
         <div class="carousel-inner">
            <div class="carousel-item active">
               <img
                  src="../assets/images/ar1.jpeg"
                  class="d-block w-100"
                  alt="..."
               />
            </div>
            <div class="carousel-item">
               <img
                  src="../assets/images/ar2.jpg"
                  class="d-block w-100"
                  alt="..."
               />
            </div>
         </div>
      </div>

      <div class="v-header-overlay"></div>
      <div class="v-header__info">
         <h1 class="v-header__title">
            WE ARE "COMPANY NAME". AND WE ARE RESPONSIBLE
         </h1>
         <h5 class="v-header__subtitle">
            “Company name” is a modern, ambitious company with A team of qualified
            TECHNICIANS. We are ready to support you by fixing any problems with
            your appliance.
         </h5>
         <button class="btn-header btn btn-danger">CALL US NOW!</button>
         <button class="btn-header btn btn-outline-light">
            SCHEDULE A VISIT
         </button>
      </div>
   </div>
</template>

<script>
export default {
   name: 'v-header-img',
   components: {},
}
</script>

<style>
.v-header-img {
   position: relative;
   width: 100%;
}

.v-header-overlay {
   position: absolute;
   top: 0;
   left: 0;
   width: 100%;
   height: 100%;
   z-index: 1;
   background: rgb(0, 0, 0);
   opacity: 0.3;
}
.v-header__info {
   position: absolute;
   top: 30%;
   left: 0;
   z-index: 10000;
   width: 100%;
}

.v-header__title {
   color: white;
   font-weight: 900;
   font-size: 80px;
}
.v-header__subtitle {
   color: white;
   font-style: italic;
   margin-top: 30px;
}
.btn-header {
   font-weight: 900;
   border-radius: 0;
   margin-right: 10px;
   margin-top: 30px;
   padding: 12px 20px;
}
</style>
