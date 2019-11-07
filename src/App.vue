<template>
  <v-app id="inspire">
  

    <v-app-bar color="primary" 
      app
      clipped-left
     
    >
     
      <v-toolbar-title>Wallet</v-toolbar-title>
    </v-app-bar>

    <v-content backgorund-color="primary" >
   
      <v-container background-color="primary" class="fill-height" fluid>
<Chart/>
      </v-container>
    </v-content>
   <BottNav/>
  </v-app>
</template>

<script>
import BottNav from './components/BottNav.vue';
import Chart from './components/Chart.vue'

  export default {
    props: {
      source: String,
    },
      components: {
      BottNav,
      Chart
   
     
    },
    data: () => ({
      drawer: null,
    }),
    created () {
      this.$vuetify.theme.dark = true
    },
  }
</script>