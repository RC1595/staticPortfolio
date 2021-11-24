<template>
  <v-app id ="main">
    <v-app-bar
      app
      color="primary"
      dark
    >
      <div class="d-flex align-center">

      </div>

      <v-spacer></v-spacer>

    </v-app-bar>

    <v-main>
      <router-view/>
    </v-main>
  </v-app>
</template>

<script>

export default {
  name: 'App',

  data: () => ({
    //
  }),
};
</script>

<style>
#main {
  background-image:linear-gradient( rgb(21, 104, 160), rgb(68, 170, 238)) ;
}

</style>
