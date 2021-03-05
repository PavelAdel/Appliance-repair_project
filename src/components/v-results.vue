<template>
   <div class="v-results" id="numbers">
      <div class="container">
         <div class="v-results__subtitle">SOME INTERESTING NUMBERS</div>
         <h2 class="v-results__title">OUR RESULTS</h2>
         <div class="row">
            <div class="col">
               <div class="v-results__number">386</div>
               <div class="v-results__text">Repairs Completed</div>
            </div>
            <div class="col">
               <div class="v-results__number">99.2 %</div>
               <div class="v-results__text">Positive Feedback</div>
            </div>
            <div class="col">
               <div class="v-results__number">254</div>
               <div class="v-results__text">Satisfied Clients</div>
            </div>
            <div class="col">
               <div class="v-results__number">$ 100000</div>
               <div class="v-results__text">Money Saved</div>
            </div>

         </div>
      </div>
   </div>
</template>

<script>
export default {
   name: 'v-results',
}
</script>

<style>
.v-results {
   padding: 80px 0;
}
.v-results__subtitle {
   font-size: 14px;
   font-weight: 900;
   letter-spacing: 2px;
   color: rgb(173, 173, 173);
   margin-bottom: 10px;
}
.v-results__title {
   font-weight: 900;
   font-size: 42px;
   letter-spacing: 2px;
   margin-bottom: 40px;
}
.v-results__number {
   font-size: 50px;
   font-weight: 700;
   font-family: serif;
   color: rgb(201, 44, 44);
}
.v-results__text {
   font-size: 20px;
   font-weight: 500;
   color: rgb(141, 141, 141);
}

</style>
