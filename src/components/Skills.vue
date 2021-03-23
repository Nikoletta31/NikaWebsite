<template>
  <div class="section3">
<div class="white">
<h2>

What are my skills?
</h2>

<div class="container1">
    
    <div class="col skill" v-b-tooltip.hover title="JavaScript"><i class="fab fa-js-square fa-5x"></i></div>
     <div class="col skill" v-b-tooltip.hover title="CSS3"><i class="fab fa-css3-alt fa-5x"></i></div>
      <div class="col skill" v-b-tooltip.hover title="HTML"><i class="fab fa-html5 fa-5x"></i></div>
      <div class="col skill" v-b-tooltip.hover title="SASS"><i class="fab fa-sass fa-5x"></i></div>
   
        
    <div class="col skill" v-b-tooltip.hover title="Bootstrap"><i class="fab fa-bootstrap fa-5x"></i></div>
     <div class="col skill" v-b-tooltip.hover title="VueJs"><i class="fab fa-vuejs fa-5x"></i></div>
      <div class="col skill" v-b-tooltip.hover title="Github"><i class="fab fa-github fa-5x"></i></div>
      <div class="col skill" v-b-tooltip.hover title="PHP"><i class="fab fa-php fa-5x"></i></div>
  

               
    
     <div class="col skill" v-b-tooltip.hover title="Adobe Photoshop"><img src="@/assets/adobe.png" /></div>
      <div class="col skill" v-b-tooltip.hover title="Illustrator"><img src="@/assets/adobe-illustrator.png" /></div>
      
    
</div>
</div>
 <b-modal centered v-model="modalShow" hide-footer hide-header>Hello From Modal!</b-modal>

  </div>

</template>

<script>
export default {
  name: "Skills",
data() {
    return {
        modalShow: false,
    }
}
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">

@import "@/assets/styles/skills.scss";


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
