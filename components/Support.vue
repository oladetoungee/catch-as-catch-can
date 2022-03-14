<template>
  <div class="support">
    <div class="support-info">
      <div class="support-heading">
        <h1 class="support-heading">We offer online  <br />tutorial classes</h1>
      </div>
      <div class="support-text">
        Would you prefer to take our online classes?
      </div>
    </div>
    <div class="support-details">
      <div>
        <img src="~assets/images/onlineclass1.jpg" alt="" class="support-img" />
      </div>
      <div class="support-links">
        
        <div class="link-info">
          Click <nuxt-link to="" class="support-link">here</nuxt-link> to 
          schedule an online session or send an
          email to
          <nuxt-link to="" class="support-link">mgeetutors@gmail.com</nuxt-link>
        </div>
      </div>
    </div>
  </div>
</template>
<script>
export default {};
</script>
<style>
.support {
  margin: 80px;
  display: flex;
  justify-content: space-between;
}
.support-info {
  margin-top: 80px;
}
.support-heading {
  color: #1b202a;
  font-size: 100px;
  line-height: 100px;
}
.support-text {
  font-size: 20px;
  line-height: 46px;
  color: #55585e;
}
.support-img {
  border-radius: 30px;
}
.support-details {
  position: relative;
}
.support-links {
  background-color: #ffffff;
  box-shadow: 0px 40px 80px rgba(164, 164, 164, 0.17);
  border-radius: 24px;
  padding: 24px 40px 24px 24px;
  width: 350px;
  position: absolute;
  top: 440px;
  right: 280px;
}
.link-info {
  font-size: 16px;
  line-height: 24px;
  color: #55585e;
  margin-top: 10px;
}
.support-link {
  text-decoration: none;
  color: #bbb809;
}
</style>
