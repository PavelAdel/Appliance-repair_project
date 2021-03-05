<template>
   <div class="v-brands" id="work">

         <img class="v-brands__img" src="../assets/images/img-logo.png" alt="..." />
         <div class="v-brands__image-overlay d-flex justify-content-center align-items-center">
            <div class="v-brands__title">
               WE SPECIALIZE IN:
            </div>
         </div>

   </div>
</template>

<script>
export default {
   name: 'v-brands',
}
</script>

<style scoped>
.v-brands {
   position: relative;
   width: 100%;
}

.v-brands__img {
   display: block;
   width: 100%;
   height: 350px;

}

.v-brands__image-overlay {
   position: absolute;
   top: 0;
   left: 0;
   width: 100%;
   height: 100%;
   background: black;
   opacity: 0.3;

}
.v-brands__title {
   color: #fff;
   font-size: 40px;
   font-weight: 800;
}

</style>
