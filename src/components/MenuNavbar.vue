<template lang="">
    <ul>
        <li :class="indexMenu===i ? 'active':''" v-for="(element,i) in menuElements" :key="element+i" @click="setActive(i)">
            {{element}}
        
        </li>
    </ul>
    
</template>
<script>
export default {
    data(){
        return{
            menuElements:["CHARACTERS","COMICS","MOVIE","TV","GAMES","COLLECTIBLES","VIDEOS","FANS","NEWS","SHOP"],
            indexMenu:0
        }
    },
    methods: {
        setActive(i){
            this.indexMenu=i;
        }
        
    },
    
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
        display: flex;
        flex-direction: column;
        &:hover{
           color:var(--color-primary ); 
           cursor:pointer;
        }
        
    }
}
.active{
    color:var(--color-primary ); 

}
.active::after{
    content: "";
    width: 100%;
    height: 3px;
    background-color: var(--color-primary);

}

    
</style>