<template>
  <div id="app" class="bg-dark">
    <div id="nav">
      <router-link to="/">Home</router-link> |
      <router-link to="/checkout">Checkout</router-link>
    </div>
    <router-view/>
  </div>
</template>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

#nav {
  padding: 30px;
}

#nav a {
  font-weight: bold;
  color: goldenrod;
}

#nav a.router-link-exact-active {
  color: gold;
}
</style>
