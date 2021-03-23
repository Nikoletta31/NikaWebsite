<template>
  <div class="section5">

<div>
    <h2>Want to know more or have a question for me? :)</h2>
     <div class="call">
   <div class="contact" @click="gitGo"><i class="fab fa-github fa-2x"></i></div>
   <div class="contact" @click="mailTo"><i class="far fa-envelope fa-2x"></i></div>
   <div class="contact" @click="linkGo"><i class="fab fa-linkedin-in fa-2x"></i></div>
    <div class="contact" @click="twittGo"><i class="fab fa-twitter fa-2x"></i></div>
 </div>
 <p>Nika Kharebava <i class="far fa-copyright"></i> 2021 </p>
</div>


  </div>

</template>

<script>
export default {
  name: "Other",
data() {
    return {
        modalShow: false,
    }
}, 
methods: {
  gitGo() {
    window.location.href = 'https://github.com/Nikoletta31';
  }, 
    linkGo() {
    window.location.href = 'https://www.linkedin.com/in/nika-kharebava-70175a145/';
  }, 
    twittGo() {
    window.location.href = 'https://twitter.com/Nikoletta3108';
  },
     mailTo() {
    window.location.href = 'mailto:nika1kharebava@gmail.com';
  },

}
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">

@import "@/assets/styles/other.scss";


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
