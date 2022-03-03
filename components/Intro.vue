<template>
    <div class="intro">
        <div class="intro-text">
            <h1>
                A better way to do <br/>your local and international <br/> deliveries
            </h1>
            <p class="intro-info">
               SHiiP is a platform that helps take care of your <br/>
                delivery and waybill while you have more time to <br/>
                handle business and serve your customers better. 
            </p>
            <div class="intro-btns">
                <button class="started">Get started with SHiiP</button>
                <nuxt-link class="explore" to="">Explore Documentation</nuxt-link>
            </div>
        </div>
        <div class="intro-img">

        </div>
    </div>
</template>
<script>
export default {
    
}
</script>
<style>
.intro {
    margin: 60px 0 60px 80px;
}
.intro-btns {
    margin-top: 10px;
}
    h1 {
      font-weight: bold;
        font-size: 56px;
        line-height: 64px;
       
        color: #005FC5;  
    }
    .intro-info {
        font-size: 24px;
        line-height: 36px;
        color: #1B202A;
    }
    .started {
        background-color: #005FC5;
        border-radius: 16px;
        padding: 16px 24px;
        color: #FFFFFF
    }
    .explore {
        text-decoration: none;
       color: #005FC5;
       margin: 0px 10px;
       line-height: 44px;

    }
</style>