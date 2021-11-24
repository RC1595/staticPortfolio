<template>
  <div>
    <div>
      <SiteHeader/>
    </div>
    <div id="container">
      <v-card id="card">
      <p>Ryan Carlson is a recent graduate of Innotech College in the Full-Stack Development program.
        Non excepteur proident Lorem Lorem. Reprehenderit excepteur exercitation aute id laboris cillum aliqua ex. Cupidatat amet labore fugiat eu.
        Nulla cillum elit deserunt ullamco ullamco cupidatat incididunt occaecat incididunt. Consequat nulla tempor commodo proident nulla anim eiusmod mollit non duis. 
        Nulla elit elit laboris nostrud amet incididunt esse veniam.</p>
        </v-card>
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
    name: 'About',
    components: {
      SiteHeader,
      SiteFooter
    }
  }
</script>

<style scoped>
#container {
  align-items: center;
  justify-items: center;
}
#card {
  margin-top: 20vh;
  margin-bottom: 20vh;
  width: 65vw;
  text-align: center;
  margin-left: 15vw;
  background-color: rgb(17, 89, 148);
}
p {
  color:thistle;
}
#footer {
    position: fixed;
    bottom: 0;
    width:100%;
}

</style>
