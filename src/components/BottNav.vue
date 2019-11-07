<template>
<div class="overflow-hidden">
  
    <v-bottom-navigation
      color="primary"
      max-height="40px"
    >
      <v-btn>
       
        <v-icon>mdi-history</v-icon>
      </v-btn>

      <v-btn>
        
        <v-icon>mdi-heart</v-icon>
      </v-btn>

       <v-btn>
        
        <v-icon>mdi-heart</v-icon>
      </v-btn>

      <v-btn>
      
        <v-icon>mdi-map-marker</v-icon>
      </v-btn>
    </v-bottom-navigation>
</div>
</template>

<script>
  export default {
    data () {
      return {
        activeBtn: 1,
        showNav: true,
      }
    },
  }
</script>

