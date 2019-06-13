<template>
  <div>
    <header>MENU</header>
    <hr />
    <div class="menu">
      <br /><router-link to="/projects">PROJECTS</router-link><br />
      <router-link to="/biography">BIOGRAPHY</router-link><br />
      <router-link to="/">JOB EXPERIENCE</router-link><br />
      <router-link to="/contacts">CONTACTS</router-link>
    </div>
    <router-link to="/" class="backBtn">BACK</router-link>
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
hr {
  width: 30px;
  float: left;
  border: lawngreen solid 2px;
}

.menu {
  text-align: left;
  width: 100%;
  background-color: black;
  font-size: 1.5rem;
  line-height: 2.5rem;
}
</style>
