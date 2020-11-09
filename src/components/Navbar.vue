<template>
 <nav>
  
  <v-app-bar flat app-bar color="deep-purple accent-2" dark>
   
   <v-app-bar-nav-icon @click="drawer = !drawer"></v-app-bar-nav-icon>
   
  <v-toolbar-title class="text-uppercase dark--text">
   <span class="font-weight-light">
    ToDo
   </span>
   <span>Dhammavira</span>
  </v-toolbar-title>
  <v-spacer></v-spacer>
  <v-btn text color="dark">
   <span class="text-uppercase dark--text">Sign Out</span>
   <v-icon right>mdi-login</v-icon>
  </v-btn>
  </v-app-bar>
  <v-navigation-drawer v-model="drawer" app class="blue lighten-2">
   <p>test</p>
  </v-navigation-drawer>
 </nav>
</template>

<script>
 export default {
  data() {
   return {
    drawer: false,
     
   }
  },
   
 }
</script>

<style lang="scss" scoped>

</style>