<template>
  <section id="hero">
    <div class="row no-gutters">
      <v-img
        style="min-height: calc(100vh - 50px);"
        src="https://images.unsplash.com/photo-1487017159836-4e23ece2e4cf?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=1951&q=80"
      >
        <v-container class="fill-height">
          <v-row class="white--text mx-auto" justify="center" align="center">
            <h1 class="white--text text-center col col-12">
              <span
                class="font-weight-light"
                :class="
                  $vuetify.breakpoint.smAndDown ? 'display-1' : 'display-2'
                "
              >
                WELCOME TO
              </span>
              <br />
              <span
                class="font-weight-black"
                :class="
                  $vuetify.breakpoint.smAndDown ? 'display-3' : 'display-4'
                "
              >
                VUETIFY
              </span>
            </h1>
            <v-btn
              dark
              type="button"
              class="align-self-end"
              depressed
              fab
              outlined
              rounded
            >
              <v-icon dark>mdi-chevron-double-down</v-icon>
            </v-btn>
          </v-row>
        </v-container>
      </v-img>
    </div>
  </section>
</template>

<script>
export default {
  name: "Welcome",

  mounted() {
    console.log(this.$vuetify.breakpoint);
  }
};
</script>
