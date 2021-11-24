<template>
    <div>
    <div>
        <SiteHeader/>
    </div>
    <div>
        <div id="projects">
            <h3>
                Check out my projects on Github!
            </h3>
            <a id="link" href="https://github.com/RC1595?tab=repositories">Github Repository</a>
        </div>
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
        name: 'Projects',
        components: {
            SiteFooter, SiteHeader
        }
    }
</script>

<style scoped>
#projects {
    margin-top: 25vh;
    margin-bottom: 20vh;
    text-align:center;
}
#link {
    color:aqua;
}
#footer {
    position: fixed;
    bottom: 0;
    width:100%;
}


</style>