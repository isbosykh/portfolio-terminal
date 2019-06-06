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
  height: 100%;
  padding: 10px;
  a {
    color: inherit;
    cursor: pointer;
  }
  header {
    font-size: 2rem;
    text-align: left;
  }

  hr {
    width: 30px;
    float: left;
    border: lawngreen solid 2px;
  }
  .backBtn {
    position: relative;
    display: block;
    bottom: 0;
    right: 0;
    margin-top: 2rem;
    font-size: 2rem;
  }
}
</style>
