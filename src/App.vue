<template>
  <div id="app">

    <router-view />
  </div>
</template>

<style lang="scss">

* {
  padding:0; 
  margin: 0; 
  box-sizing: border-box;
}

body {
 background: rgb(250,197,162);
background: linear-gradient(164deg, rgba(250,197,162,1) 0%, rgba(250,172,120,1) 21%, rgba(250,163,106,1) 79%);
}

#app {
  font-family: 'Poppins', sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

#nav {
  padding: 30px;

  a {
    font-weight: bold;
    color: #2c3e50;

    &.router-link-exact-active {
      color: #42b983;
    }
  }
}
</style>
