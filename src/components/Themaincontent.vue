<template >
    <div class="img-box">
        <img src="/imgs/jumbotron.jpg" class="img-fluid" alt="">
    </div>
    <div class="container">
        <div class="row row-cols-6  g-4 py-5">
            <div class="col" v-for="fumetti in fumettiList">
                <div class="card">
                    <img :src="fumetti.thumb" class="card-img-top" alt="...">
                    <div class="card-body">
                        <h5 class="card-title">{{fumetti.series}}</h5>
                        
                    </div>
                </div>
            </div>

        </div>
    </div>
</template>
<script>
export default {
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
</style>