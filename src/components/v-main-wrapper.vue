<template>
   <div class="v-main-wrapper">
      <v-nav-bar></v-nav-bar>
      <v-header-img></v-header-img>
      <v-info></v-info>
      <v-service></v-service>
      <v-brands></v-brands>
      <v-results></v-results>
      <v-contacts></v-contacts>
      <v-footer></v-footer>
      <v-sub-footer></v-sub-footer>
   </div>
</template>

<script>
import vNavBar from './v-nav-bar'
import vHeaderImg from './v-header-img'
import vInfo from './v-info'
import vService from './v-service'
import vBrands from './v-brands'
import vResults from './v-results'
import vContacts from './v-contacts'
import vFooter from './v-footer'
import vSubFooter from './v-sub-footer'
export default {
   name: 'v-main-wrapper',
   components: {
      vNavBar,
      vHeaderImg,
      vInfo,
      vService,
      vBrands,
      vResults,
      vContacts,
      vFooter,
      vSubFooter
   },
   data() {
      return {

      }
   }
}
</script>

<style></style>
