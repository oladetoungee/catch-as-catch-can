<template>
  <div>
    <Heading/>
    <Intro/>
    <Benefit/>
    <Support/>
    <Advert/>
    <Partners/>
     <Setup/>
    <Businesses/>
    <Footerr/>
  </div>
</template>

<script>
import Benefit from '../components/Benefit.vue'
export default {
  components: { Benefit },
  
}
</script>
<style>
  html {
    font-family: GT Walsheim Pro;
  }
  button {
    opacity: 1;
  }
  button:hover {
    opacity: 0.8;
  }
  
</style>