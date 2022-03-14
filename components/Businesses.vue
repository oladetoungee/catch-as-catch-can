<template>
  <div class="businesses">
    <div class="business-info">
      <p class="business-p1">
        We are going GLOBAL!
      </p>
      <p class="business-p2">
        With study centers strategically located in three southwestern states of Nigeria, <br/> we won't stop until our centers are all over Africa
      </p>
      <p class="business-p2">At our study centers, our students get to enjoy a whole lot of benefits.</p>
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
          <h3 class="benefit-topic">First class Learning Facilities</h3>
          <p class="benefit-info">
            Amazing facilities are available for student activities, classroom sessions and administrative activities.
            <nuxt-link to="" class="benefit-links">Book us now!</nuxt-link>
          </p>
        </div>
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
          <h3 class="benefit-topic">Effecient Library Services</h3>
          <p class="benefit-info">
            Our libraries are ever open to students for to get the best use of collections to satisfy their information needs.
            <nuxt-link to="" class="benefit-links">Book us now!</nuxt-link>
          </p>
        </div>
        
      </div>
      
      
    </div>
    <div class="learn-container">
        <button class="learn-btn">
          Visit us at any of our centers
        </button>
      </div>
  </div>
</template>
<script>
export default {};
</script>
<style>
.businesses {
  margin: 50px 0;
}
.circle {
    width: 350px;
}
.bus {
  width: 150px;
  border-radius: 10px;
  background-color: white;
 padding: 10px;
}


.business-p1 {
    font-weight: 500;
font-size: 40px;
line-height: 46px;
text-align: center;
color: #bbb809;
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
    display: flex;
    justify-content: space-around;
    
    
}
.business-benefit {
  transition: 1s ease;
  padding: 20px;
 width: 387px;
height: 297px;
background: #F9F9F9;
box-shadow: 0px 40px 80px rgba(164, 164, 164, 0.17);
border-radius: 33px;
}
.business-benefit:hover {
  -webkit-transform: scale(0.9);
-ms-transform: scale(0.9);
transform: scale(0.9);
transition: 1s ease;
}

.learn-btn {
    background: #bbb809;
     border: 1px solid #bbb809;
        box-shadow: 0px 1px 2px #bbb809;
border-radius: 16px;
padding: 32px 24px;
color: #F5F5F5;

}
.learn-container {
    display: flex;
    justify-content: center;
}
</style>
