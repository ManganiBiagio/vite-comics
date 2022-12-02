<template lang="">
    <div class="container">
        <nav class="nav-box">
            <div ><img src="/imgs/dc-logo.png" class="img-box" alt=""></div>
            
            <MenuNavbarVue></MenuNavbarVue>
            

        </nav>
    </div>
</template>
<script>
import MenuNavbarVue from './MenuNavbar.vue';
export default {
    components:{MenuNavbarVue}
    
}
</script>
<style lang="scss" scoped>
.nav-box {
    padding: 1rem 0 0 0;
    display:flex;
    align-items: center;
    justify-content:space-between;
}
.img-box{
    height: 60px;
    object-fit: cover;
}
    
</style>