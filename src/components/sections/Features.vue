<template>
  <section id="features" class="grey lighten-3">
    <div class="py-8"></div>
    <v-container class="text-center">
      <h2 class="display-2 font-weight-bold mb-3">VUETIFY FEATURES</h2>
      <v-responsive class="mx-auto mb-12" style="width: 56px;">
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
      <v-row>
        <div class="col-md-4 col-12">
          <v-card flat class="py-12 px-4 lighten-5" color="grey">
            <div>
              <v-avatar color="primary" size="88">
                <v-icon size="36" dark>mdi-account-group-outline</v-icon>
              </v-avatar>
            </div>
            <v-card-title
              class="justify-center font-weight-black text-uppercase mb-4"
            >
              Vibrant Community
            </v-card-title>
            <v-card-subtitle class="subtitle-1">
              Lorem ipsum dolor sit amet consectetur adipisicing elit. Iusto
              cupiditate sint possimus quidem atque harum excepturi nemo velit
              tempora! Enim inventore fuga, qui ipsum eveniet facilis obcaecati
              corrupti asperiores nam
            </v-card-subtitle>
          </v-card>
        </div>
        <div class="col-md-4 col-12">
          <v-card flat class="py-12 px-4 lighten-5" color="grey">
            <div>
              <v-avatar color="primary" size="88">
                <v-icon size="36" dark>mdi-update</v-icon>
              </v-avatar>
            </div>
            <v-card-title
              class="justify-center font-weight-black text-uppercase mb-4"
            >
              Frequent Updates
            </v-card-title>
            <v-card-subtitle class="subtitle-1">
              Sed ut elementum justo. Suspendisse non justo enim. Vestibulum
              cursus mauris dui, a luctus ex blandit. Lorem ipsum dolor sit amet
              consectetur adipisicing elit. qui ipsum eveniet facilis obcaecati
              corrupti consectetur adipisicing elit.
            </v-card-subtitle>
          </v-card>
        </div>
        <div class="col-md-4 col-12">
          <v-card flat class="py-12 px-4 lighten-5" color="grey">
            <div>
              <v-avatar color="primary" size="88">
                <v-icon size="36" dark>mdi-shield-outline</v-icon>
              </v-avatar>
            </div>
            <v-card-title
              class="justify-center font-weight-black text-uppercase mb-4"
            >
              Long-term Support
            </v-card-title>
            <v-card-subtitle class="subtitle-1">
              Lorem ipsum dolor sit amet consectetur adipisicing elit. Iusto
              cupiditate sint possimus quidem atque harum excepturi nemo velit
              tempora! Enim inventore fuga, qui ipsum eveniet facilis obcaecati
              corrupti asperiores nam
            </v-card-subtitle>
          </v-card>
        </div>
      </v-row>
    </v-container>
    <div class="py-8"></div>
  </section>
</template>

<script>
export default {
  name: "Features"
};
</script>
