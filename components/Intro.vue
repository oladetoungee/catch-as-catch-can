<template>
    <div class="intro">
        <div class="intro-text">
            <h1>
               Creating a platform where <br/> learners can undergo tutorial classes <br/>  to facilitate academic excellence. 
            </h1>
            <p class="intro-info">
               M’Gee Tutors is an initiative that gives every learner a chance <br/> 
               using methods that match their unique learning styles <br/> irrespective of their academic background or performance.
            </p>
            <div class="intro-btns">
                <button class="started">Get started with M'Gee</button>
                <nuxt-link class="explore" to="">Book a Session with us Today</nuxt-link>
            </div>
        </div>
        <div class="intro-img">
            <img src="~assets/images/classroom.jpg" alt="">
        </div>
    </div>
</template>
<script>
export default {
    
}
</script>
<style>
.intro {
    display: flex;
    justify-content: space-between;
    margin: 60px 0 60px 80px;
}
.intro-text {
    width: 900px;
}
.intro-btns {
    margin-top: 10px;
}
    h1 {
      font-weight: bold;
        font-size: 56px;
        line-height: 64px;
       
        color: #bbb809;  
    }
    .intro-info {
        font-size: 24px;
        line-height: 36px;
        color: #1B202A;
    }
    .started {
        background-color: #bbb809;
        border-radius: 16px;
        padding: 16px 24px;
        color: #FFFFFF;
         border: 1px solid #bbb809;
        box-shadow: 0px 1px 2px #bbb809;
    }
    .explore {
        text-decoration: none;
       color: #bbb809;
       margin: 0px 10px;
       line-height: 44px;

    }
</style>