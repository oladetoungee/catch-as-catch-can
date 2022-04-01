<template>
  <div class="benefit-container">
    <h4 class="benefit-heading">Why M'Gee Tutors?</h4>
    <div class="benefit-items">
      <div class="benefit-item">
        
        <h3 class="benefit-topic">Personalized Learning Plan</h3>
        <p class="benefit-info">
         Every student can learn, but not every student can learn the same way. At M'Gee Tutors, we give our students the individualized attention
         they might not get in their various traditional classrooms.
          <nuxt-link to="" class="benefit-links">Book us now!</nuxt-link>
        </p>
      </div>
       <div class="benefit-item">
        
        <h3 class="benefit-topic">Effective Tutors</h3>
        <p class="benefit-info">
          Our tutors are patient, strategic, encouraging, ethusiastic and professional. 
          They create a personalized learning plan for each student and build a curriculum 
          that’s in line with the student’s particular goals.
          <nuxt-link to="" class="benefit-links">Book us now!</nuxt-link>
        </p>
      </div>
       <div class="benefit-item">
        
        <h3 class="benefit-topic">Affordable rates</h3>
        <p class="benefit-info">
          At M'Gee Tutors, it’s our goal to make our  tutoring services affordable, convenient available to students everywhere,
           we provide economically-disadvantaged high school and primary school students with standard curriculum 
           which they might not get in their various underserved schools.

          <nuxt-link to="" class="benefit-links">Book us now!</nuxt-link>
        </p>
      </div>
       <div class="benefit-item">
        
        <h3 class="benefit-topic">We are going Global.</h3>
        <p class="benefit-info">
          We are expanding in markets across states in Nigeria and we are starting with Ogun State and Oyo State. We also plan to partner with schools and other educational institutions to have masterclasses at intervals for students who might not necessarily be a part of us. 
          Our mission is to establish similar centers across Nigeria and Africa as a whole. 
            
          <nuxt-link to="" class="benefit-links">Book us now!</nuxt-link>
        </p>
      </div>
       <div class="benefit-item">
        
        <h3 class="benefit-topic">Personal Interest Facilitation</h3>
        <p class="benefit-info">
           We are facilitated enough not just to help them with their academics but also to help them discover
            and grow their personal interests, entrepreneurial skills, leadership skills, vocational training and talent development.
          <nuxt-link to="" class="benefit-links">Book us now!</nuxt-link>
        </p>
      </div>
       <div class="benefit-item">
        
        <h3 class="benefit-topic">Online Classes</h3>
        <p class="benefit-info">
         We are equally available for students whose locations do not match our current study centres, for this reason, 
         we have a platform where online classes can be available for students that are not in our current geographical location. 
          <nuxt-link to="" class="benefit-links">Book us now!</nuxt-link>
        </p>
      </div>
       <div class="benefit-item">
        
        <h3 class="benefit-topic">Home Tutoring</h3>
        <p class="benefit-info">
          We have several parents and guardians that prefer that to have their children tutored in the comfort of their homes, so consequently,
           we have selected tutors that visit to home to these students to tutor them.
          <nuxt-link to="" class="benefit-links">Book us now!</nuxt-link>
        </p>
      </div>
       <div class="benefit-item">
        
        <h3 class="benefit-topic">Library Services</h3>
        <p class="benefit-info">
          We have libraries at our differnt study centers for our students and other students to use to 
          complement their academic books and also to give them the chance to explore knowledge.
          <nuxt-link to="" class="benefit-links">Book us now!</nuxt-link>
        </p>
      </div>
       <div class="benefit-item">
        
        <h3 class="benefit-topic">Library Services</h3>
        <p class="benefit-info">
          We have libraries at our differnt study centers for our students and other students to use to 
          complement their academic books and also to give them the chance to explore knowledge.
          <nuxt-link to="" class="benefit-links">Book us now!</nuxt-link>
        </p>
      </div>
    </div>
  </div>
</template>
<script>
export default {};
</script>
<style>
body {
    background-color: #F9F9F9;
}
.benefit-topic {
  color: #bbb809;
}

.benefit-container {
  margin: 80px 60px;
  
}
.benefit-heading {
  text-align: center;
  color: #34373f;
  font-weight: 500;
  font-size: 32px;
  line-height: 44px;
  text-align: center;
  color: #34373f;
}
.benefit-items {
    margin-top: 20px;
    display: grid;
    grid-template-rows: 1fr 1fr 1fr;
    grid-template-columns: 1fr 1fr 1fr;
    gap: 30px;
}
.benefit-item {
  transition: 1s ease;
  padding: 20px;
  border: 1px solid #ded8d8;
  width: 400px;
  height: 350px;
  border-radius: 33px;
}
.benefit-item:hover {
  -webkit-transform: scale(0.9);
-ms-transform: scale(0.9);
transform: scale(0.9);
transition: 1s ease;
}
.benefit-links {
  text-decoration: none;
  color: #bbb809;
}
.benefit-links:hover {
  text-decoration: none;
  opacity: 0.7;
}
/* .image-main {
  position: absolute;
 
} */
/* .image-shadow {
    position: absolute;
    top: 645px;
    left: 80px;
} */
h3 {
  margin-top: 20px;
}
.benefit-info {
  font-size: 16px;
  line-height: 34px;
  color: #34373f;
  margin-top: 10px;
}
</style>
