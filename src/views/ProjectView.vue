<template>
  <div>
    <header>PROJECT.NAME</header>
    <h4>VUE.JS</h4>
    <hr />
    <div class="text">
      <p>
        <br />HERE IS DESCRIPTION OF PROJECT THAT DEVELOPED ON "FRAMEWORK OR
        TECHNOLOGY NAME". <br /><br /><a href="">REPOSITORY.LINK</a>
      </p>
    </div>
    <router-link to="/projects" class="backBtn">BACK</router-link>
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
