<template>
  <div>
    <header>PROJECTS</header>
    <hr />
    <div class="menu">
      <router-link to="/main">VANILLA</router-link>
      <router-link to="/main">VUE.JS</router-link>
      <router-link to="/main">BOOTSTRAP</router-link>
      <router-link to="/main">GOVNO</router-link>
    </div>
    <Copyright />
  </div>
</template>

<script>
import Copyright from "@/components/Copyright";

export default {
  name: "MainView",
  components: {
    Copyright
  }
};
</script>

<style lang="scss" scoped>
header {
  font-size: 2rem;
  text-align: left;
  padding: 0 10px;
}

hr {
  width: 30px;
  float: left;
  margin-left: 10px;
  border: lawngreen solid 2px;
}

.menu {
  display: flex;
  flex-direction: column;
  text-align: left;
  width: 100%;
  background-color: black;
  font-size: 1.5rem;
  line-height: 2.5rem;
  padding: 0 10px;
}
</style>
