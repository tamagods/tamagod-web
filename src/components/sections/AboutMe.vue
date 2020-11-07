<template>
  <section id="about-me">
    <div class="py-6"></div>
    <v-container class="text-center">
      <h2 class="display-2 font-weight-bold mb-3">ABOUT ME</h2>
      <v-responsive class="mx-auto mb-8" style="width: 56px;">
        <hr
          role="separator"
          aria-orientation="horizontal"
          class="mb-1 v-divider theme--light"
        />
        <hr
          role="separator"
          aria-orientation="horizontal"
          class="v-divider theme--light"
        />
      </v-responsive>
      <v-responsive
        class="mx-auto title font-weight-light mb-8"
        style="max-width: 720px;"
      >
        Vuetify is the #1 component library for Vue.js and has been in active
        development since 2016. The goal of the project is to provide users with
        everything that is needed to build rich and engaging web applications
        using the Material Design specification. It accomplishes that with a
        consistent update cycle, Long-term Support (LTS) for previous versions,
        responsive community engagement, a vast ecosystem of resources and a
        dedication to quality components.
      </v-responsive>
      <v-avatar class="elevation-12 mb-12" size="128">
        <v-img alt="." src="../../assets/profile-about-me.jpg"></v-img>
      </v-avatar>
    </v-container>
  </section>
</template>

<script>
export default {
  name: "AboutMe"
};
</script>
