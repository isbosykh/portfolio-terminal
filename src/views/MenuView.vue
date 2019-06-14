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
  </div>
</template>

<script>
export default {
  name: "MainView"
};
</script>
