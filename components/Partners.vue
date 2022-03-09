<template>
  <div class="partners">
    <div class="map">
      <img class="map" src="~assets/images/worldmap.svg" alt="" />
    </div>
    <div class="partner-info">
      <p class="partner-p1">
        Do you want to have <br />
        your child tutored, <br />
        in the comfort of your home?
      </p>
      <p class="partner-p2">
        We’ve got you covered <br />
        with our team of professional and trustworthy tutors 
      </p>
      <!-- <div class="images">
           <img class="image" src="~assets/images/dhl.svg" alt="" />
            <img class="image" src="~assets/images/barimike.svg" alt="" />
             <img class="image" src="~assets/images/kwik.svg" alt="" />
              <img class="image" src="~assets/images/gig.svg" alt="" />
               <img class="image" src="~assets/images/gg.svg" alt="" />
                <img class="image" src="~assets/images/truq.svg" alt="" />
      </div>
      <div class="images">
           <img class="image" src="~assets/images/express.svg" alt="" />
            <img class="image" src="~assets/images/star.svg" alt="" />
             <img class="image" src="~assets/images/us.svg" alt="" />
              
      </div> -->
    </div>
  </div>
</template>
<script>
export default {};
</script>
<style>
.partners {
    display: flex;
    justify-content: space-between;
    margin: 60px 80px;
}
.map {
    border-radius: 20px;
}
.partner-info {
    display: flex;
    flex-direction: column;
    align-items: flex-end;
    text-align: right;
    margin-top: 150px;
}
.partner-p1 {
    font-weight: 500;
    font-size: 40px;
    line-height: 65px;
    color: #1B202A;
}
.partner-p2 {
    font-weight: 500;
font-size: 20px;
line-height: 43px;
color: #55585E;
margin-top: 20px;
}
.images {
    margin-top: 30px;
}
.image {
    margin: 0 20px;
}
</style>
