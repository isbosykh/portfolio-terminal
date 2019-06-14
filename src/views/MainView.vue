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
