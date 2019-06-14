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
