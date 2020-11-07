<template>
  <v-app>
    <v-app-bar app color="white" dark>
      <div class="d-flex align-center">
        <v-img
          alt="Vuetify Logo"
          class="shrink mr-2"
          contain
          src="https://cdn.vuetifyjs.com/images/logos/vuetify-logo-light.png"
          transition="scale-transition"
          width="40"
        />

        <v-img
          alt="Vuetify Name"
          class="shrink mt-1"
          contain
          min-width="100"
          src="https://cdn.vuetifyjs.com/images/logos/vuetify-name-light.png"
          width="100"
        />
      </div>

      <v-spacer></v-spacer>
    </v-app-bar>

    <v-main>
      <Dashboard msg="Hello Vuetify !" />
    </v-main>

    <v-footer
      class="justify-center"
      style="background-color: rgb(41, 41, 41); border-color: rgb(41, 41, 41); color: white;"
    >
      <Footer />
    </v-footer>
  </v-app>
</template>

<script>
import Dashboard from "@/views/Dashboard";
import Footer from "@/components/Footer";

export default {
  name: "App",

  components: {
    Dashboard,
    Footer
  },

  data: () => ({
    //
  })
};
</script>
