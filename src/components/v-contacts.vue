<template>
   <div class="v-contacts">
      <div class="container">
         <div class="v-contacts__text">CONTACT US</div>
         <div class="v-contacts__title">CONTACTS</div>
         <div class="v-contacts__subtitle">
            We provide services THROUGHOUT Los Angeles County
         </div>

         <div class="row">
            <div class="col">
               <form class="">
                  <div class="mb-3">
                     <label
                        for="exampleInputName"
                        class="form-label d-flex v-contacts__label"
                        >PLEASE ENTER YOUR NAME</label
                     >
                     <input
                        type="email"
                        class="form-control v-contacts__custom"
                        id="exampleInputEmail1"
                        aria-describedby="emailHelp"
                     />
                     <div id="emailHelp" class="form-text d-flex">
                        This field is required.
                     </div>
                  </div>
                  <div class="mb-3 ">
                     <label
                        for="exampleInputNumber"
                        class="form-label d-flex v-contacts__label"
                     >
                        PLEASE ENTER YOUR PHONE NUMBER.
                     </label>
                     <input
                        type="text"
                        class="form-control v-contacts__custom"
                        id="exampleInputNumber"
                     />
                  </div>
                  <label
                     for="exampleInputPassword1"
                     class="form-label d-flex v-contacts__label"
                  >
                     READY TO SCHEDULE A VISIT
                  </label>
                  <div class="mb-3 form-check">
                     <input
                        type="checkbox"
                        class="form-check-input input_custom"
                        id="exampleCheck1"
                     />
                     <label
                        class="form-check-label d-flex v-contacts__check-label"
                        for="exampleCheck1"
                        >Yes</label
                     >
                  </div>
                  <div class="mb-3 form-check v-contacts__checkbox">
                     <input
                        type="checkbox"
                        class="form-check-input"
                        id="exampleCheck1"
                     />
                     <label
                        class="form-check-label d-flex v-contacts__check-label"
                        for="exampleCheck1"
                        >No</label
                     >
                  </div>
                  <div class="mb-3 ">
                     <label
                        for="exampleInputPassword1"
                        class="form-label d-flex v-contacts__label"
                     >
                        DATE/TIME
                     </label>
                     <input
                        type="text"
                        class="form-control v-contacts__custom"
                        id="exampleInputDate"
                        placeholder="01/01 2pm"
                     />
                     <div id="emailHelp" class="form-text d-flex">
                        Please enter date and time in any format
                     </div>
                  </div>

                  <div class="d-grid gap-2">
                     <button
                        type="submit"
                        class="v-contacts__btn btn btn-danger v-contacts__sublabel"
                     >
                        SEND
                     </button>
                  </div>
               </form>
            </div>
            <div class="col">
               <div class="d-flex v-contacts__info">
                  <div class="v-contacts__icon">
                     <img
                        class="v-contacts__icon-svg"
                        src="../assets/images/icons/vectorpaint1.svg"
                        alt="."
                     />
                  </div>
                  <div class="v-contacts__aadress">
                     331 Foothill Rd, Beverly Hills, CA 90210, USA
                  </div>
               </div>
               <div class="d-flex v-contacts__info">
                  <div class="v-contacts__icon">
                     <img
                        class="v-contacts__icon-svg"
                        src="../assets/images/icons/vectorpaint (1).svg"
                        alt="."
                     />
                  </div>
                  <div class="v-contacts__phone">
                     (900)001-10001
                  </div>
               </div>
               <div class="d-flex v-contacts__info">
                  <div class="v-contacts__icon">
                     <img
                        class="v-contacts__icon-svg"
                        src="../assets/images/icons/vectorpaint (2).svg"
                        alt="."
                     />
                  </div>
                  <div class="v-contacts__email">
                     mail@companyname.com
                  </div>
               </div>
            </div>
         </div>
      </div>
   </div>
</template>

<script>
export default {
   name: 'v-contacts',
}
</script>

<style>
.v-contacts {
   background: rgb(248, 248, 248);
   padding-bottom: 70px;
}
.v-contacts__text {
   font-size: 14px;
   font-weight: 900;
   letter-spacing: 2px;
   color: rgb(173, 173, 173);
   padding-top: 70px;
}
.v-contacts__title {
   font-weight: 900;
   font-size: 42px;
   letter-spacing: 2px;
   margin-bottom: 30px;
}
.v-contacts__subtitle {
   color: rgb(133, 133, 133);
   font-weight: 500;
   font-size: 21px;
   margin-bottom: 60px;
}

/**** form **********************/

.v-contacts__label {
   font-size: 12px;
   color: rgb(134, 134, 134);
   line-height: 0.4;
   font-weight: 700;
   margin-top: 30px;
}
.v-contacts__custom {
   background-color: #ebebeb;
}
.v-contacts__btn {
   border-radius: 0;
   font-size: 14px;
   font-weight: 700;
}
.v-contacts__checkbox {
   margin-top: -15px;
}

.v-contacts__custom {
   border-radius: 0;
}

.v-contacts__custom::placeholder {
   font-size: 15px;
   color: rgb(105, 105, 105);
}

.v-contacts__check-label {
   color: rgb(90, 90, 90);
}

.v-contacts__info {
   padding-top: 30px;
}
.v-contacts__aadress,
.v-contacts__phone,
.v-contacts__email {
   color: rgb(90, 90, 90);
   font-style: italic;
   font-size: 16px;
   margin-left: 10px;
}
.v-contacts__email {
   color: rgb(150, 31, 31);
}

.v-contacts__icon-svg {
   width: 25px;
   padding-bottom: 10px;
}
.input_custom {
   outline: none;
}

.form-control:hover,
.form-control:focus {
   border-color: #cccccc;
   -webkit-box-shadow: none;
   box-shadow: none;
   background: rgb(226, 226, 226);
   transition: 0.3s;
}
</style>
