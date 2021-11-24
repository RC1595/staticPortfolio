<template>
    <div>
        <div>
            <SiteHeader/>
        </div>
        <div id="list">
            <p>
                Ryan is familiar with the following technologies.
            </p>
            <ul>
                <li>HTML</li>
                <li>CSS</li>
                <li>JavaScript</li>
                <li>Vue.js</li>
                <li>Python</li>
                <li>Flask</li>
                <li>MariaDB</li>
                <li>Apache</li>
                <li>GCP</li>
                <li>AWS</li>
            </ul>
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
        name: 'Skills',
        components: {
            SiteFooter, SiteHeader
        }
    }
</script>

<style scoped>
#list {
    text-align: center;
    margin-top: 15vh;
    color:aliceblue;
}
#list > ul {
    list-style-type: none;
}
#footer {
    position: fixed;
    bottom: 0;
    width:100%;
}

</style>