<template>
  <div>
    <header>PROJECTS</header>
    <hr />
    <div class="content">
      <router-link to="/project">CATS API</router-link>
      <router-link to="/project">THIS PORTFOLIO</router-link>
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
