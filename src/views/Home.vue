<template>
  <div class="home">

  <AboutMe/>
    <Next />
    <Skills/>
  <Projects/>
  <Other/>
  </div>
</template>

<script>
// @ is an alias to /src

import AboutMe from "@/components/AboutMe.vue";
import Next from "@/components/Next.vue";
import Projects from "@/components/Projects.vue";
import Skills from "@/components/Skills.vue";
import Other from "@/components/Other.vue";

export default {
  name: "Home",
  components: {
  AboutMe,
    Next, 
    Projects,
    Skills, 
    Other
  }
};
</script>
