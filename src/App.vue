<script>
import TheNavbarVue from './components/TheNavbar.vue';
import TheBanner1Vue from './components/TheBanner1.vue';
import TheBanner2Vue from './components/TheBanner2.vue';
import TheFooterVue from './components/TheFooter.vue';

export default {
  components:{TheBanner1Vue,TheBanner2Vue,TheNavbarVue,TheFooterVue}
 }


</script>

<template>
  <div class="container">
    <TheNavbarVue></TheNavbarVue>
  </div>
 
</template>

<style lang="scss">
@use "bootstrap/scss/bootstrap";
@use "./styles/general.scss";

</style>
