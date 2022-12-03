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
                                <li v-for="link in dcComicsList "><a href="#">{{link}}</a></li>
                               
    
                            </ul>
                        </div>
                        <div>
                            <span> 
                             SHOP
                            </span>
                            <ul>
                                <li v-for="link in shopList "><a href="#">{{link}}</a></li>
                                
                               
    
                            </ul>
                        </div>

                    </div>
                    <div class="box-link">
                        <div>
                            <span> 
                             DC
                            </span>
                            <ul>
                                <li v-for="link in dcList "><a href="#">{{link}}</a></li>
                    
    
                            </ul>
                        </div>

                    </div>
                    <div class="box-link">
                        <div>
                            <span> 
                             SITES
                            </span>
                            <ul>
                                <li v-for="link in sitesList "><a href="#">{{link}}</a></li>
                               
    
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
    data(){
        return{
            dcComicsList:["Characters","Comics","Movies","Tv","Games","Videos","News"],
            shopList:["Shop DC","Shop DC Collectibles"],
            dcList:["Terms Of Use","Privacy policy(New)","Ad Choices","Advertising","Jobs","Subsriptions","Talent Workshops","CPSC Certificates","Rating","Shop Help","Contact Us"],
            sitesList:["DC","MAD Magazine","DC Kids","DC Universe","DC Power Visa"]
        }
    }

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
            text-align: center;
            a{
                color: var(--color-link);
                text-decoration: none;
                &:hover{
                  color: var(--color-primary);
                  transition: all .2s;
                }
            }
           
            
            
        }
    }

}

.box-link {
    padding: 0 1rem;
    text-align: center;
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