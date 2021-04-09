<template>
  <div class="section4">



<div class="project" data-aos="zoom-in" data-aos-duration="1000" @click="seeIt = !seeIt">

<div class="project-text-box"  :style="[seeIt ? {opacity:0.9} : null]">
<h2 class="project-text">Actioneo VueJs</h2>
<button @click="visible">Learn more</button>
</div>
    </div>



<div class="project2" data-aos="zoom-in" data-aos-duration="1000" @click="seeIt1 = !seeIt1">
 
<div class="project-text-box" :style="[seeIt1 ? {opacity:0.9} : null]">
<h2 class="project-text">Weather App API VueJs</h2>
<button @click="gitGo3">Learn more</button>
</div>


    </div>
 <div class="project3" data-aos="zoom-in" data-aos-duration="1000" @click="seeIt2 = !seeIt2">
<div class="project-text-box" :style="[seeIt2 ? {opacity:0.9} : null]">
<h2 class="project-text">Fruits API VueJs</h2>
<button @click="gitGo2">Learn more</button>
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
        seeIt: false, 
        seeIt1: false, 
        seeIt2: false
    }
}, 
methods: {

visible(){
 this.$router.push('Actioneo')
},
visible1(){
 this.seeIt1 = true; 
},
visible2(){
 this.seeIt2 = true; 
},


  gitGo1() {
    window.location.href = 'https://github.com/Nikoletta31';
  }, 
    gitGo2() {
    window.location.href = 'https://github.com/Nikoletta31/API-VueJs';
  }, 
    gitGo3() {
    window.location.href = 'https://github.com/Nikoletta31/Weather-App-VueJs';
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
