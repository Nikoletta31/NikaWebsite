<template>
  <div class="section6">
<div class="white">
<h2>

What can I do ?
</h2>

<div class="container1">
    
 <p>Landing Pages</p>
 <p>API connections</p>
 <p>Debugging</p>
 <p>Creating projects with Vue.Js</p>
      
    
</div>
</div>
 <b-modal centered v-model="modalShow" hide-footer hide-header>Hello From Modal!</b-modal>

  </div>

</template>

<script>
export default {
  name: "ToDo",

};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">

@import "@/assets/styles/todo.scss";


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
