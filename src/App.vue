<template>
  <div id="app">
    <router-view />
  </div>
</template>

<style lang="scss">
body {
  height: 100%;
  margin: 0;
  background-color: black;
  color: lawngreen !important;
}

#app {
  text-transform: uppercase;
  font-family: "vt323", sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  overflow: hidden;
  a {
    color: inherit;
    cursor: pointer;
  }
}
</style>
