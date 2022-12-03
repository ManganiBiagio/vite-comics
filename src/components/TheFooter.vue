<template lang="">
   <div class="box-footer">
    <div class="container">
        <div class="d-flex">
            <div class="btn-box">
                <button class="my-btn">SIGN-UP NOW!</button>
            </div>
            <div class="link-box">
                <div class="txt-footer">FOLLOW US</div>
                <div><img src="/imgs/footer-facebook.png" alt=""></div>
                <div><img src="/imgs/footer-twitter.png" alt=""></div>
                <div><img src="/imgs/footer-youtube.png" alt=""></div>
                <div><img src="/imgs/footer-pinterest.png" alt=""></div>
                <div><img src="/imgs/footer-periscope.png" alt=""></div>

            </div>

        </div>

    </div>

   </div>
</template>
<script>
export default {
    
}
</script>
<style lang="scss">
.box-footer{
    background-color: var(--color-third);
    padding: 1rem 0;
}
.my-btn{
    color: white;
    background-color: transparent;
    border: 3px solid var(--color-primary);
    padding: 10px;
    &:hover{
        background-color: var(--color-primary);
        transition:background-color .3s;
        
        
    }

}
.link-box{
    display: flex;
    align-items: center;
    gap: 1rem;
    margin-left:auto ;
}
.txt-footer{
    color: var(--color-primary);
}
</style>