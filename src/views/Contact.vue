<template>
    <div>
        <div>
            <SiteHeader/>
        </div>
        <v-card id="card" class="justify-center" elevation="3">
        <div>
            <h3>Contact: </h3>
            <p class="link"><a href="https://ca.linkedin.com/in/c-ryan-carlson-84885772">LinkdIn</a></p>
            <p class="link"><a href="https://github.com/RC1595?tab=repositories">Github</a></p>
        </div>
        
        <div>
            <v-btn id="btn" @click="quote">Request a Quote</v-btn>
        </div>
        </v-card>
        <div>
            <SiteFooter/>
        </div>
    </div>
</template>

<script>
    import SiteFooter from '../components/SiteFooter.vue'
    import SiteHeader from '../components/SiteHeader.vue'
    export default {
        name: 'Contact',
        components: {
            SiteFooter, SiteHeader
        },
        methods: {
            quote(){
                window.location = "mailto:ryancarls@gmail.com";
            }
        }
        
    }
</script>

<style scoped>
#card {
    width: 15vw;
    background-color:rgb(32, 97, 151);
    margin-top: 20vh;
    margin-left:39vw;
}
.link > a{
    color: aqua;
    margin-left: 5vw;
}
h3 {
    color:aliceblue;
    margin-left: 4vw;
}
#btn {
    margin-left: 2vw;
}

#footer {
    position: fixed;
    bottom: 0;
    width:100%;
}

</style>