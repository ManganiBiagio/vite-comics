<template lang="">
    <div class="box-banner-2">
        <div class="container">
            <div class="d-flex ">
                <div class="banner-2-links">
                    <div class="box-link">
                        <div>
                            <span> 
                             DC COMICS
                            </span>
                            <ul>
                                <li>link</li>
                                <li>link</li>
                                <li>link</li>
                                <li>link</li>
                                <li>link</li>
                                <li>link</li>
                                <li>link</li>
    
                            </ul>
                        </div>
                        <div>
                            <span> 
                             SHOP
                            </span>
                            <ul>
                                <li>link</li>
                                <li>link</li>
                               
    
                            </ul>
                        </div>

                    </div>
                    <div class="box-link">
                        <div>
                            <span> 
                             DC
                            </span>
                            <ul>
                                <li>link</li>
                                <li>link</li>
                                <li>link</li>
                                <li>link</li>
                                <li>link</li>
                                <li>link</li>
                                <li>link</li>
                                <li>link</li>
                                <li>link</li>
                                <li>link</li>
                                <li>link</li>
                    
    
                            </ul>
                        </div>

                    </div>
                    <div class="box-link">
                        <div>
                            <span> 
                             SITES
                            </span>
                            <ul>
                                <li>link</li>
                                <li>link</li>
                                <li>link</li>
                                <li>link</li>
                                <li>link</li>
                               
    
                            </ul>
                        </div>
                       
                    </div>


                </div>
                <div class="banner-2-img-box">
                    <img src="/imgs/dc-logo-bg.png"   alt="">

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
.box-banner-2 {
    background-image: url(/imgs/footer-bg.jpg);
    background-repeat: no-repeat;
    background-size: cover;
    overflow: hidden;





}

.banner-2-links {
    padding-top: 2rem;
    color: white;
    display: flex;

    ul {
        padding: unset;
        list-style: none;
        li{
            color: lightgray;
            
        }
    }

}

.box-link {
    padding: 0 1rem;
    span{
        font-size: 1.2rem;
        font-weight: bold;
    }
}

.banner-2-img-box {
    margin-left: auto;
    scale: 1.3;

    img {
        height: 350px;

    }



}
</style>