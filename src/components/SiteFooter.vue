<template>
    <div id="footer">
        <template>
            <v-footer
                color="primary lighten-1"
                padless>
                <v-row
                justify="center"
                no-gutters>
                
                <v-btn
                    v-for="link in links"
                    :key="link"
                    :to="link.routeUrl"
                    color="white"
                    text
                    rounded
                    class="my-2">
                    {{ link.title }}
                </v-btn>
                <v-col
                    class="primary lighten-2 py-4 text-center white--text"
                    cols="12">
                    {{ new Date().getFullYear() }} — <strong>Ryan Carlson</strong>
                </v-col>
                </v-row>
            </v-footer>
        </template>
    </div>
</template>

<script>
    export default {
        name: 'SiteFooter',
        data: () => ({
            links: [{
                title: 'Home',
                routeUrl: '/'
            },
            {
                title: 'About',
                routeUrl: '/about'
            },
            {
                title: 'Contact',
                routeUrl: '/contact'
            },
            {
                title: 'Projects',
                routeUrl: '/projects'
            },
            {
                title: 'Skills',
                routeUrl: '/skills'
            }
            ],
        }),
    }
</script>

<style scoped>


</style>