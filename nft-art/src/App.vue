<template>
  <v-app>
    <v-container>
    <Header />
    <v-main>
      <router-view />
    </v-main>
    <Footer />
    </v-container>
  </v-app>
</template>

<script>
import Header from './components/Header.vue'
import Footer from './components/Footer.vue'

export default {
  name: "App",
  components: {
    Header,
    Footer
  },

  data: () => ({
    //
  }),
};
</script>
