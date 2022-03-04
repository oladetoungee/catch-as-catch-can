<template>
  <div class="businesses">
    <div class="business-info">
      <p class="business-p1">
        SHiiP works with small, medium and large businesses
      </p>
      <p class="business-p2">
        Run your business smoothly by integrating SHiiP API to your <br/> websites,
        e-commerce stores, or marketplace.
      </p>
      <p class="business-p2">With SHiiP API, you will be able to</p>
    </div>
    <div class="platform-info">
      <div class="benefits">
        
        <div class="business-benefit">
          <img
            src="~assets/images/wallet-check.svg"
            alt=""
            class="image-main"
          />
          <img
            src="~assets/images/walletshadow.svg"
            alt=""
            class="image-shadow"
          />
          <h3 class="benefit-topic">Compare Delivery Fees</h3>
          <p class="benefit-info">
            You can see and compare delivery fees from over 50 companies and get
            the best rates from them. Delivery companies like DHL Express, GIG,
            FedEx/Redstar, USPS, Gokada, Kwik, Barimike, and so much more are
            available on SHiiP.
            <nuxt-link to="" class="benefit-links">Try it now!</nuxt-link>
          </p>
        </div>
        <div class="business-benefit benefit-shift">
          <img
            src="~assets/images/wallet-check.svg"
            alt=""
            class="image-main"
          />
          <img
            src="~assets/images/walletshadow.svg"
            alt=""
            class="image-shadow"
          />
          <h3 class="benefit-topic">Compare Delivery Fees</h3>
          <p class="benefit-info">
            You can see and compare delivery fees from over 50 companies and get
            the best rates from them. Delivery companies like DHL Express, GIG,
            FedEx/Redstar, USPS, Gokada, Kwik, Barimike, and so much more are
            available on SHiiP.
            <nuxt-link to="" class="benefit-links">Try it now!</nuxt-link>
          </p>
        </div>
        
      </div>
      <div class="markets">
             <img src="~assets/images/circle.svg" alt="" class="circle" />
              <img src="~assets/images/jumia.svg" alt="" class="jumia" />
               <img src="~assets/images/jiji.svg" alt="" class="image-main" />
                <img src="~assets/images/slot.svg" alt="" class="image-main" />
                 <img src="~assets/images/seller.svg" alt="" class="image-main" />
                  <img src="~assets/images/konga.svg" alt="" class="image-main" />
                  
        </div>
      
    </div>
    <div class="learn-container">
        <button class="learn-btn">
          Learn more about SHiiP API Integration
        </button>
      </div>
  </div>
</template>
<script>
export default {};
</script>
<style>
.platform-info {
    display: flex;
}
.business-p1 {
    font-weight: 500;
font-size: 40px;
line-height: 46px;
text-align: center;
color: #000000;
margin: 15px 0;
}
.business-p2 {
    font-size: 20px;
line-height: 23px;
text-align: center;
color: #000000;
margin: 5px 0;
}
.benefits {
    margin-top: 20px;
    
}
.business-benefit {
    margin: 30px 70px;
 width: 387px;
height: 297px;
background: #F9F9F9;
box-shadow: 0px 40px 80px rgba(164, 164, 164, 0.17);
border-radius: 33px;
}
.benefit-shift {
    margin-left: 120px;
}
.learn-btn {
    background: #005FC5;
border-radius: 16px;
padding: 32px 24px;
color: #F5F5F5;

}
.learn-container {
    display: flex;
    justify-content: center;
}
</style>
