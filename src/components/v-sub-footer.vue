<template>
   <div class="v-sub-footer">
      <div class="container">
         <div
            class="v-sub-footer__up-btn d-flex justify-content-sm-end "
         >
            <a href="#top">
               <img
                  class="v-sub-footer__img"
                  src="../assets/images/vectorpaint.svg"
                  alt=""
               />
            </a>
         </div>
         <div class="v-sub-footer__text">
            Copyright © 2021 Compane name
         </div>
      </div>
   </div>
</template>

<script>
export default {
   name: 'v-sub-footer',
}
</script>

<style>
.v-sub-footer {
   height: 90px;
   background: rgb(48, 48, 48);
}
.v-sub-footer__text {
   color: rgb(196, 196, 196);
   padding-top: 35px;
   font-size: 16px;

}


.v-sub-footer__img {
   width: 30px;
   height: 100%;
}
</style>
