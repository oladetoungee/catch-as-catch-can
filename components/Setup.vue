<template>
    <div class="set-up">
        <div class="setup-infos">
            <div class="setup-info-heading">
               <p>It’s simple and easy <br/> to set up</p>
            
            </div>
             <div class="setup-info">
                <img src="~assets/images/Line.svg" alt="">
                 <p class="setup-p">Download the SHiiP App on Apple store or Play Store, <br/> or visit the Web App.</p>
            </div>
             <div class="setup-info info-fade">
                  <img src="~assets/images/Line.svg" alt="">
                 <p class="setup-p">Sign up and set up your profile.</p>
            </div>
            <div class="setup-info info-fade">
                 <img src="~assets/images/Line.svg" alt="">
                 <p class="setup-p">Book your delivery and share the tracking links with <br/> your customers right away!</p>
            </div>
            <div >
                <button class="setup-btn"> Find out more</button>
            </div>
        </div>
        <div class="setup-img">
            <div class="ecllipse">
                <img src="~assets/images/Ellipse.svg" alt="">
            </div>
            <div class="ecllipsee">
                <img src="~assets/images/Ellipse.svg" alt="">
            </div>
            <div class="ecllipseee">
                <img src="~assets/images/Ellipse.svg" alt="">
            </div>
            <div class="phone">
                 <img src="~assets/images/phone.svg" alt="">
            </div>
        </div>
    </div>
</template>
<script>
export default {
    
}
</script>
<style>
.set-up {
    background-color: #005FC5;
    display: flex;
    justify-content: space-between;
}
.setup-infos {
    margin: 70px 80px;
}
.info-fade {
    opacity: 0.3;
}
.setup-info {
    display: flex;
   
    font-size: 20px;
line-height: 46px;
color: #FFFFFF;

margin: 40px 0;
} 
.setup-p {
    margin-left: 30px;
}
.setup-btn {
   
padding: 25px 25px;
background-color: #F5F5F5;
border-radius: 16px;
font-weight: 500;
/* font-size: 20px; */
/* line-height: 40px; */
color: #005FC5;
}

.setup-img {
    position: relative;
    display: flex;
   margin: 150px 100px ;
}
.setup-info-heading {
    font-weight: 500;
    margin: 40px 0;
font-size: 40px;
line-height: 48px;
color: #FFFFFF;
}
.phone {
    position: absolute;
    right: 70px;
}
.ecllipse {
    position: absolute;
    left: 5px;
    top: 70px;

}
.ecllipsee {
    position: absolute;
    left: 5px;
    top: 20px;

}

</style>