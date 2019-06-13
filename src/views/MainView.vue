<template>
  <div>
    <header>WELCOME</header>
    <hr />
    <div class="text">
      <p>
        <br />HI.<br /><br />
        MY AM IS ILJA. MY AM INSPIRED FRONTEND DEVELOPER.<br />
        JUST KIDDING.<br /><br />
        USE ARROWS ON YOUR KEYBOARD FOR NAVIGATE AND ENTER FOR SUBMIT YOUR
        CHOICE.<br /><br />
        LET`S START.<br /><br />
        PRESS <router-link to="menu">ENTER</router-link> TO BEGIN.
      </p>
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
hr {
  width: 30px;
  float: left;
  border: lawngreen solid 2px;
}

.text {
  text-align: left;
  width: 100%;
  background-color: black;
  font-size: 1.5rem;
  p {
    margin: 0;
  }
}
</style>
