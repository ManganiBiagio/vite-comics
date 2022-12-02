<script>
import TheNavbarVue from './components/TheNavbar.vue';
import TheBanner1Vue from './components/TheBanner1.vue';
import TheBanner2Vue from './components/TheBanner2.vue';
import TheFooterVue from './components/TheFooter.vue';

export default {
  components: { TheBanner1Vue, TheBanner2Vue, TheNavbarVue, TheFooterVue }
}


</script>

<template>

  <TheNavbarVue></TheNavbarVue>
  <div class="main-content">
    <div class="container">
      <div class="content">
        Content goes here
      </div>
    </div>

  </div>
  <TheBanner1Vue></TheBanner1Vue>



</template>

<style lang="scss">
@use "bootstrap/scss/bootstrap";
@use "./styles/general.scss";

.main-content {
  background-color: black;
  .content{
    padding: 2rem 0;
    color: white;
  }

  

}
</style>
