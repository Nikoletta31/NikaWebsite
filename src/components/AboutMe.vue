<template>
  <div class="section1">
    <div class="text-section1">
<h1>Hello,</h1>
<h2>I am <span>Nika</span>.</h2>
<h3>Creative front-end developer</h3>
</div>
<div class="info-section1">
 <img src="@/assets/photo-me.png" />

 <div class="call">
   <div class="contact" @click="gitGo"><i class="fab fa-github fa-2x" ></i></div>
   <div class="contact" @click="mailTo"><i class="far fa-envelope fa-2x"></i></div>
   <div class="contact" @click="linkGo"><i class="fab fa-linkedin-in fa-2x"></i></div>
    <div class="contact" @click="twittGo"><i class="fab fa-twitter fa-2x"></i></div>
 </div>

 <div class="photo-info" data-aos="zoom-in" data-aos-duration="1000">
 <p>
      My name is Nika and I am a front-end developer, based in
      Paris. <br />
      Being a translator and working as a sales assistant, I decided to change
      my life. I choose to become a front-end developer and I think this job
      suits me really well.<br />
      I love challenges, working with the details and finding the solutions. <br>
      
 
    </p>
</div>
</div>
  </div>
</template>

<script>
export default {
  name: "AboutMe",
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

@import "@/assets/styles/header.scss";


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
