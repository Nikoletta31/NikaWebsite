<template>
  <div class="section4">



<div class="project" data-aos="zoom-in" data-aos-duration="1000" @click="gitGo1">

<div class="project-text-box">
<h2 class="project-text">Actioneo VueJs</h2>
</div>
    </div>



<div class="project2" data-aos="zoom-in" data-aos-duration="1000" @click="gitGo3">
 
<div class="project-text-box">
<h2 class="project-text">Weather App API VueJs</h2>
</div>


    </div>
 <div class="project3" data-aos="zoom-in" data-aos-duration="1000" @click="gitGo2">
<div class="project-text-box">
<h2 class="project-text">Fruits API VueJs</h2>
</div>
    </div>
  </div>

</template>

<script>
export default {
  name: "Projects",
data() {
    return {
        modalShow: false,
    }
}, 
methods: {
  gitGo1() {
    window.location.href = 'https://github.com/Nikoletta31';
  }, 
    gitGo2() {
    window.location.href = 'https://github.com/Nikoletta31/API-VueJs';
  }, 
    gitGo3() {
    window.location.href = 'https://github.com/Nikoletta31/nikakharebava';
  },


}
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">

@import "@/assets/styles/projects.scss";


ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
