<template>
  <div>
    <header>MENU</header>
    <hr />

    <div class="content">
      <router-link to="/projects">PROJECTS</router-link>
      <router-link to="/biography">BIOGRAPHY</router-link>
      <router-link to="/experience">JOB EXPERIENCE</router-link>
      <router-link to="/contacts">CONTACTS</router-link>
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
