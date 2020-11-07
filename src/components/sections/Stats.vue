<template>
  <section id="stats">
    <v-parallax
      :height="$vuetify.breakpoint.smAndDown ? '700' : '500'"
      src="https://images.unsplash.com/photo-1510915228340-29c85a43dcfe?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=1950&q=80"
    >
      <v-container class="fill-height">
        <v-row class="mx-auto">
          <div class="col-md-3 col-12">
            <div class="text-center">
              <div class="display-3 font-weight-black mb-4">24k</div>
              <div class="title font-weight-regular text-uppercase">
                Github Stars
              </div>
            </div>
          </div>
          <div class="col-md-3 col-12">
            <div class="text-center">
              <div class="display-3 font-weight-black mb-4">330+</div>
              <div class="title font-weight-regular text-uppercase">
                Releases
              </div>
            </div>
          </div>
          <div class="col-md-3 col-12">
            <div class="text-center">
              <div class="display-3 font-weight-black mb-4">1m</div>
              <div class="title font-weight-regular text-uppercase">
                Downloads/mo
              </div>
            </div>
          </div>
          <div class="col-md-3 col-12">
            <div class="text-center">
              <div class="display-3 font-weight-black mb-4">5m</div>
              <div class="title font-weight-regular text-uppercase">
                Total Downloads
              </div>
            </div>
          </div>
        </v-row>
      </v-container>
    </v-parallax>
  </section>
</template>

<script>
export default {
  name: "Stats"
};
</script>
