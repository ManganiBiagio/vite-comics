<template >
    <div class="img-box">
        <img src="/imgs/jumbotron.jpg" class="img-fluid" alt="">
    </div>
    <div class="container">
        <div class="title-main">CURRENT SERIES</div>
        <div class="row row-cols-6  g-4 py-5">
            <div class="col" v-for="fumetto in fumettiList">
                <Fumetticard :fumetto="fumetto"></Fumetticard>
                
            </div>

        </div>
        <div class="text-center py-3">
            <button class="my-btn" >LOAD MORE</button>
        </div>
    </div>
</template>
<script>

import Fumetticard from './Fumetticard.vue';
export default {
    components:{ Fumetticard },
    props:{
        fumettiList:Array
    }

}
</script>
<style lang="scss" scoped>
.img-box {
    height: 400px;
    overflow: hidden;
}
.card{
    background-color: transparent;
    border: unset;
    color: white;
    
}
.my-btn{
    color: white;
    background-color: var(--color-primary);
    border: 3px solid var(--color-primary);
    padding: 10px;
    &:hover{
        background-color: white;
        color:black;
        border: 3px solid white;
        transition:background-color .3s;
        
        
    }

}
.title-main{
    color: white;
    background-color: var(--color-primary);
    position: relative;
    top:-15px;
    font-size: 1.5rem;
    display: inline;
    padding: .5rem;
}
</style>