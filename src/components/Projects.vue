<template>
  <div class="section4">


<div class="project" data-aos="zoom-in" data-aos-duration="1000">
<h2>Actioneo</h2>
<h3>(VueJs)</h3>
<p>Project in team realized for the lawyer's company. <br>
    Working with CRM system, databases and API endpoints.
</p>
    </div>

 <div class="project" data-aos="zoom-in" data-aos-duration="1000">
<h2>Fruit API</h2>
<h3>(VueJs)</h3>
<p>SPA with the connection of API endpoints.
    <br>
    Using GET,POST,DELETE requests and treating the data.
</p>
    </div>

    <div class="project" data-aos="zoom-in" data-aos-duration="1000">
<h2>Pers. website</h2>
<h3>(HTML,CSS,JS)</h3>
<p>First personal portfolio website.
  <br> It was realized using JavaScript, SASS and JS Animations.
</p>
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
