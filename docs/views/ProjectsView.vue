<template>
  <div>
    <header>PROJECTS</header>
    <hr />
    <div class="menu">
      <br /><span>VANILLA</span><br />
      <span>NE VANIKLLA</span><br />
      <span>KILLA KILLA</span><br />
      <span>KUKLA CHACKI</span>
    </div>
    <router-link to="/menu" class="backBtn">BACK</router-link>
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
  span {
    text-decoration: underline;
    cursor: pointer;
  }
}
</style>
