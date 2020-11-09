<template>
  <v-app class="grey lighten-4">
    <Navbar />
    <v-main>
      <router-view></router-view>
    </v-main>
  </v-app>
</template>

<script>
//import HelloWorld from './components/HelloWorld';
import Navbar from './components/Navbar'

export default {
  components : {
Navbar
  },
  name: "App",

  data: () => ({
    //
  }),
};
</script>
