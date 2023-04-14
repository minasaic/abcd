<template>
  <div id="app">
    <div id="div1">
      <h1>1nstagram</h1>
    </div>
    <nav id="div2">
      <p>メニュ</p>
      <router-link to="/">home</router-link>
      <br>
      <router-link to="/serch">serch</router-link>
      <br>
      <router-link to="/create-post">create post</router-link>
      <br>
      <router-link to="my-page">my page</router-link>
    </nav>
    <div id="router">
      <router-view/>
    </div>
  </div>
</template>

<script>


  
</script>
<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #2c3e50;
}
#div1 {
  text-align: center;
}
#div2 {
  text-align: left;
}
#router{
  text-align: center;
}

/* nav {
  padding: 30px;
} */

nav a {
  font-weight: bold;
  color: #2c3e50;
}

nav a.router-link-exact-active {
  color: #42b983;
}
</style>
