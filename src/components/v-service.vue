<template>
   <div class="v-service" id="service">
      <div class="container">
         <h2 class="v-service__title">OUR SERVICES</h2>
         <div class="v-service__card d-flex justify-content-between">
            <div class="v-service__card-list">
               <img
                  class="v-service__img-custom card-img-top"
                  src="../assets/images/icons8-fridge-100.png"
                  alt="Card image cap"
               />
               <div class="card-body">
                  <h5 class="card-title">
                     Refregirator
                  </h5>
                  <p class="card-text">
                     Is your refrigerator not maintaining the correct
                     temperature? Has your icemaker stopped working? Problems
                     with the freezer? “Company name” can repair it.
                  </p>
               </div>
            </div>

            <div class="v-service__card-list">
               <img
                  class="v-service__img-custom card-img-top"
                  src="../assets/images/icons8-cooker-100.png"
                  alt="Card image cap"
               />
               <div class="card-body">
                  <h5 class="card-title">
                     Oven
                  </h5>
                  <p class="card-text">
                     We fix conventional and microwave ovens and can repair
                     cooktops and ranges, both gas and electric.
                  </p>
               </div>
            </div>

            <div class="v-service__card-list">
               <img
                  class="v-service__img-custom card-img-top"
                  src="../assets/images/icons8-tumble-dryer-100.png"
                  alt="Card image cap"
               />
               <div class="card-body">
                  <h5 class="card-title">
                     Any Household Appliance
                  </h5>
                  <p class="card-text">
                     Washer, dryer, and dishwasher repair. Whether gas or
                     electric, we can fix it.
                  </p>
               </div>
            </div>

            <div class="v-service__card-list">
               <img
                  class="v-service__img-custom card-img-top"
                  src="../assets/images/icons8-cooker-hood-100.png"
                  alt="Card image cap"
               />
               <div class="card-body">
                  <h5 class="card-title">
                     Appliance Installation
                  </h5>
                  <p class="card-text">
                     We can also install your electric appliance and ensure that
                     it is connected properly.
                  </p>
               </div>
            </div>
         </div>
      </div>
   </div>
</template>

<script>
export default {
   name: 'v-service',
}
</script>

<style>
.v-service {
   background: rgb(248, 248, 248);
   padding-bottom: 80px;
}
.v-service__title {
   padding-top: 100px;
   padding-bottom: 60px;
   font-weight: 900;
   font-size: 40px;
}
.v-service__img-custom {
   width: 100px;
   padding-top: 30px;
}
.v-service__card-list {
   width: 280px;
   background: white;
   margin: 0 15px;
   box-shadow: 0 5px 5px -5px rgba(0, 0, 0, 0.5);
}
.v-service__card-list:hover {
   box-shadow: 0 0 10px 5px rgba(221, 221, 221, 1);
   transition: 0.3s;
}
.card-title {
   font-size: 18px;
}
.card-text {
   font-size: 15px;
}
</style>
