<template>
  <v-app>
    <v-app-bar
      app
      color="black"
      dark
      
    >
      <div class="d-flex align-center">
        <v-img
          alt="Vuetify Logo"
          class="shrink mr-2"
          contain
          src="https://cdn.vuetifyjs.com/images/logos/vuetify-logo-dark.png"
          transition="scale-transition"
          width="40"
        />

        
      </div>
      <!-- <v-app-bar-nav-icon @click.stop="SideMenu"></v-app-bar-nav-icon> -->
      <v-spacer><router-link to="/" style="color:white;text-decoration:none;"><span>MUSIC SEARCH</span></router-link></v-spacer>
      
     

      <v-btn
        text
        to="/"
      >
        <span class="mr-2">HOME</span>
       
      </v-btn>
    </v-app-bar>

    <v-content>
      
      <router-view/>
    </v-content>
  </v-app>
</template>

<script>
export default {
  name: 'App',

  components: {
   
  },

  data: () => ({
    //
  }),
  
};
</script>
