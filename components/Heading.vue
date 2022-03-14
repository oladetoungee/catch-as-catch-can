<template>
    <div class="head">
        <div class="header-logo">
           <img src="~assets/images/logo1.jpg" alt="">
           
        </div>
        <div class="header-nav">
            <!-- <ul class="nav-list">
             <div class="drop"> 
                   <li class="nav-item"><nuxt-link to="">Home</nuxt-link></li>
                  
              </div>
              <div class="drop"> 
                   <li class="nav-item"><nuxt-link to="">Products</nuxt-link></li>
                   <img src="~assets/images/droparrow.svg" alt="">
              </div>
               <div class="drop"> 
                  <li class="nav-item"><nuxt-link to="">Customers</nuxt-link></li>
                   <img src="~assets/images/droparrow.svg" alt="">
              </div>
               <div class="drop"> 
                    <li class="nav-item"><nuxt-link to="">Resource</nuxt-link></li>
                   <img src="~assets/images/droparrow.svg" alt="">
              </div>
              <div class="drop"> 
                   <li class="nav-item"><nuxt-link to="">FAQ</nuxt-link></li>
                   
              </div>
              
            </ul> -->
        </div>
        <div class="header-auth">
            <!-- <li class="log-in"><nuxt-link to="">Log in</nuxt-link></li> -->
            <button class="get-started">BOOK M'GEE TUTORS</button>
        </div>
    </div>
</template>
<script>
export default {
    
}
</script>
<style>
    .head {
        display: flex;
        justify-content: space-between;
        margin: 60px 80px;
        
    }
   
    li a {
        text-decoration: none;
    }
    li {
        list-style: none;
        margin: 0 10px;
        
    }
    .nav-list {
        display: flex;
        justify-content: space-between;
        
    }
    .header-auth {
        display: flex;
        
    }
    .drop {
        display: flex;
       margin: 20px;
    }
   
   .log-in {
       margin: 20px;
   }
   .get-started {
       background-color: #bbb809;
       border: 1px solid #bbb809;
        box-shadow: 0px 1px 2px #bbb809;
        border-radius: 8px ;
        color: #FFFFFF;
        padding: 0 25px ;
   }
</style>