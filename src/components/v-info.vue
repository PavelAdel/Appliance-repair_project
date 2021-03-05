<template>
   <div class="v-info">
      <div class="container">
         <h2 class="v-info__title">SEVERAL REASONS TO TRUST "COMPANY NAME</h2>
         <div class="v-info__card d-flex justify-content-between">
            <div class="v-info__card-list">
               <img
                  class="v-info__img-custom card-img-top"
                  src="../assets/images/icons8-end-call-male-100.png"
                  alt="Card image cap"
               />
               <div class="card-body">
                  <h5 class="card-title">
                     Availability of our technicians round the clock
                  </h5>
                  <p class="card-text">
                     Always on time. We appreciate your trust and we have an
                     availability of our technicians round the clock.
                  </p>
               </div>
            </div>
            <div class="v-info__card-list">
               <img
                  class="v-info__img-custom card-img-top"
                  src="../assets/images/icons8-resume-100.png"
                  alt="Card image cap"
               />
               <div class="card-body">
                  <h5 class="card-title">
                     Licensed and qualified technicians will be at your disposal
                  </h5>
                  <p class="card-text">
                     Our technicians are experienced. Each technician has more
                     THAN 3 years of experience.
                  </p>
               </div>
            </div>
            <div class="v-info__card-list">
               <img
                  class="v-info__img-custom card-img-top"
                  src="../assets/images/icons8-time-100.png"
                  alt="Card image cap"
               />
               <div class="card-body">
                  <h5 class="card-title">
                     Speedy repairs and spare parts.
                  </h5>
                  <div class="card-text">
                     Large inventory of parts in stock* <p>*some may be readily
                     available from our partners</p>
                  </div>
               </div>
            </div>
            <div class="v-info__card-list">
               <img
                  class="v-info__img-custom card-img-top"
                  src="../assets/images/icons8-money-100.png"
                  alt="Card image cap"
               />
               <div class="card-body">
                  <h5 class="card-title">
                     Competitive rates and long term partnership
                  </h5>
                  <p class="card-text">
                     Our rates are competitive and our main goal is to build a
                     long-term partnership with our clients.
                  </p>
               </div>
            </div>
         </div>
      </div>
   </div>
</template>

<script>
export default {
   name: 'v-info',
}
</script>

<style>
.v-info {
   background: rgb(248, 248, 248);
}
.v-info__title {
   padding: 60px 0;
   font-weight: 900;
   font-size: 40px;
}
.v-info__img-custom {
   width: 100px;
}
.v-info__card-list {
   width: 300px;
}
.card-title {
   font-size: 18px;
}
.card-text {
   font-size: 15px;
}
</style>
