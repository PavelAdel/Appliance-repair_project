<template>
   <div class="v-footer" id="contact">
      <div class="container">
         <div class="d-flex justify-content-between v-footer__info">
            <div class="v-footer__title">
               STAY IN TOUCH:
               <div class="v-footer__link">
                  <a href="">URL-Link</a>
               </div>
            </div>

            <div class="v-footer__title">
               PROUDLY DEVELOPED BY:
               <div class="v-footer__link">
                  <a href="">URL-Link</a>
               </div>
            </div>
         </div>
      </div>
   </div>
</template>

<script>
export default {
   name: 'v-footer',
}
</script>

<style>
.v-footer {
   background: rgb(92, 92, 92);
   height: 200px;
}
.v-footer__info {
   padding-top: 60px;
}
.v-footer__title {
   color: white;
   font-weight: 800;
   font-size: 17px;
}
.v-footer__link {
   text-transform: uppercase;
   margin-top: 10px;
}
.v-footer__link a {
   text-decoration: none;
   color: rgb(192, 191, 191);
}
</style>
