<template>
  <div>
    <Welcome />
    <AboutMe />
    <Features />
    <Stats />
    <Blog />
  </div>
</template>

<script>
import Welcome from "@/components/sections/Welcome";
import AboutMe from "@/components/sections/AboutMe";
import Features from "@/components/sections/Features";
import Stats from "@/components/sections/Stats";
import Blog from "@/components/sections/Blog";

export default {
  name: "Dashboard",

  components: {
    Welcome,
    AboutMe,
    Features,
    Stats,
    Blog
  },

  data: () => ({
    //
  })
};
</script>
