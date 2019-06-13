<template>
  <div>
    <header>CONTACTS</header>
    <hr />
    <div class="menu">
      <br /><span>E-MAIL: <a href="">viewtohell@gmail.com</a></span
      ><br />
      <span
        >GITHUB:
        <a href="https://github.com/RonnyTod?tab=repositories"
          >github.link</a
        ></span
      ><br />
      <span
        >HEADHUNTER:
        <a href="https://hh.ru/resume/ea20134dff063d82590039ed1f587a7a6d5349"
          >headhunter.link</a
        ></span
      ><br />
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
  p {
    margin: 0;
  }
}
</style>
