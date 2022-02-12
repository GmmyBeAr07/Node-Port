<template>
  <div id="nav">
  <Navbar/>
    </div>
  <router-view/>
</template>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #172431;
}

#nav a {
  font-weight: bold;
  color: #462b66;
}

#nav a.router-link-exact-active {
  color: #14d37d;
}
</style>
