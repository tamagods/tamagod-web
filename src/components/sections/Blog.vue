<template>
  <section id="blog">
    <div class="py-8"></div>
    <v-container>
      <h2 class="display-2 font-weight-bold mb-3 text-uppercase text-center">
        Blog
      </h2>
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
      <v-row>
        <div class="col-md-4 col-12">
          <v-img
            class="mb-4"
            src="https://images.unsplash.com/photo-1423784346385-c1d4dac9893a?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=1950&q=80"
            style="height: 275px; max-width: 100%;"
          ></v-img>
          <h3 class="font-weight-black mb-4 text-uppercase">
            Mobile first &amp; Responsive
          </h3>
          <div class="title font-weight-light mb-5">
            Phasellus lorem enim, luctus ut velit eget, convallis egestas eros.
            Sed ornare ligula eget tortor tempor, quis porta tellus dictum.
          </div>
          <v-btn type="button" class="ml-n4 font-weight-black" text>
            Continue Reading
          </v-btn>
        </div>
        <div class="col-md-4 col-12">
          <v-img
            class="mb-4"
            src="https://images.unsplash.com/photo-1475938476802-32a7e851dad1?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=1950&q=80"
            style="height: 275px; max-width: 100%;"
          ></v-img>
          <h3 class="font-weight-black mb-4 text-uppercase">
            Think outside the box
          </h3>
          <div class="title font-weight-light mb-5">
            Nam ut leo ipsum. Maecenas pretium aliquam feugiat. Aenean vel
            tempor est, vitae tincidunt risus. Sed sodales vestibulum nibh.
          </div>
          <v-btn type="button" class="ml-n4 font-weight-black" text>
            Continue Reading
          </v-btn>
        </div>
        <div class="col-md-4 col-12">
          <v-img
            class="mb-4"
            src="https://images.unsplash.com/photo-1416339442236-8ceb164046f8?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=1892&q=80"
            style="height: 275px; max-width: 100%;"
          ></v-img>
          <h3 class="font-weight-black mb-4 text-uppercase">
            Small changes, big difference
          </h3>
          <div class="title font-weight-light mb-5">
            Vestibulum in dictum velit, in rhoncus nibh. Maecenas neque libero,
            interdum a dignissim in, aliquet vitae lectus. Phasellus lorem enim,
            luctus ut velit eget.
          </div>
          <v-btn type="button" class="ml-n4 font-weight-black" text>
            Continue Reading
          </v-btn>
        </div>
      </v-row>
    </v-container>
    <div class="py-6"></div>
  </section>
</template>

<script>
export default {
  name: "blog"
};
</script>
