<template>
<div>
  <div>
    <SiteHeader/>
  </div>
  <div id="text">
    <h2>Ryan Carlson</h2>
    <h3>Junior Web Developer</h3>
  </div>
  <div id="footer">
    <SiteFooter/>
  </div>
  
</div>
</template>

<script>
  import SiteFooter from '../components/SiteFooter.vue'
  import SiteHeader from '../components/SiteHeader.vue'

  export default {
    name: 'Home',
    components: {
      SiteFooter,
      SiteHeader
    },
  }
</script>

<style scoped>
#footer {
    position: fixed;
    bottom: 0;
    width:100%;
}
#text {
  text-align: center;
  margin-top: 20vh;
  color:aliceblue;
}
</style>
