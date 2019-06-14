<template>
  <div>
    <header>CONTACTS</header>
    <hr />
    <div class="content">
      <span>E-MAIL: <a href="">viewtohell@gmail.com</a></span>
      <span
        >GITHUB:
        <a href="https://github.com/RonnyTod?tab=repositories"
          >github.link</a
        ></span
      >
      <span
        >HEADHUNTER:
        <a href="https://hh.ru/resume/ea20134dff063d82590039ed1f587a7a6d5349"
          >headhunter .link</a
        ></span
      >
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
