<template>
  <div>
    <Welcome />
    <AboutMe />
  </div>
</template>

<script>
import Welcome from "@/components/sections/Welcome";
import AboutMe from "@/components/sections/AboutMe";

export default {
  name: "Dashboard",

  components: {
    Welcome,
    AboutMe
  },

  data: () => ({
    //
  })
};
</script>
