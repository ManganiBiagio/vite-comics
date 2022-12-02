<template lang="">
    <ul>
        <li v-for="element in menuElements">
            {{element}}
        
        </li>
    </ul>
    
</template>
<script>
export default {
    data(){
        return{
            menuElements:["CHARACTERS","COMICS","MOVIE","TV","GAMES","COLLECTIBLES","VIDEOS","FANS","NEWS","SHOP"]
        }
    }
    
}
</script>
<style lang="scss" scoped>
ul{
    display: flex;
    align-items: center;
    list-style: none;
    margin: unset;
    li{
        padding: 0rem .7rem;
        font-size: .7rem;
        font-weight: bold;
    }
}

    
</style>