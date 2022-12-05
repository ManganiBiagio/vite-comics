<template lang="">
    <div class="card">
                    <img :src="fumetto.thumb" class="card-img-top" alt="...">
                    <div class="card-body">
                        <h5 class="card-title">{{fumetto.series}}</h5>
                        
                    </div>
    </div>
</template>
<script>
export default {
    props:{
        fumetto:Object

    }

}
</script>
<style lang="">
    
</style>