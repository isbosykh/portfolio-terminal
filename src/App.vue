<template>
  <div id="app">
    <router-view />
  </div>
</template>

<style lang="scss">
body {
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
  h4 {
    margin: 0;
    padding: 0;
    text-align: left;
    font-weight: lighter;
  }
  .backBtn {
    position: absolute;
    display: block;
    bottom: 0;
    right: 0;
    margin: 2rem;
    font-size: 2rem;
  }
  @media screen and (min-width: 800px) {
    width: 800px;
    margin: auto;
  }
}
</style>
