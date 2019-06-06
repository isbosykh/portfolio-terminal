<template>
  <div>
    <header>BIOGRAPHY</header>
    <hr />
    <div class="text">
      <p>
        <br />BORN IN RUSSIA. 1998.<br /><br />

        GOES TO SCHOOL IN LIKE A 6 YEARS OLD AND SPENT 9 YEARS IN THERE. WHOLE
        OF THAT TIME I'VE BEEN KEEN ON VIDEOGAMES AND TECHNOLOGIES. SO THAT WAS
        A REASON WHY I CHOOSE PROGRAMMING AS PROFESSION.<br /><br />

        I STUDIED THERE FOR FOUR YEARS ON A "IT" FACULTY. I CAN'T SAY THAT IT
        WAS VERY INTERESTING OR USEFUL, BUT THAT WAS A GOOD EXPERIENCE IN A
        TEAMWORK AND PRACTICE. WHOLE OF THAT TIME I'VE BEEN KEEN ON 3D
        MODELLING, WEBDEV AND GAMEDEV. SO, I'M DONE IT. <br /><br />

        AFTER I GRADUATED IN ONE YEAR AGOI TRIED TO STUDY SOME COURSES ABOUT
        WEBDEV OR SIMILLAR, BUT NOW I CAN TELL TO ANYONE THAT IT DON'T HAVE ANY
        SENSE WITHOUT PRACTICE. ACTUALLY, FOR MY OPINION, PRACTICE - IS A 90% OF
        SUCCESFUL AND USEFUL STUDY. I HADN'T MUCH IN IT FOR THAT TIME.
        <br /><br />

        BUT IN OCTOBER 2018, I WENT IN THE OFFICE AND SAID "I WILL BE HERE TO
        WORK". THAT WAS MY COMRADE'S DIGITAL STUDIO AND THIS WAS BEGINNING TO
        THE BEGINNING OF MY ACQUAINTANCE WITH FRONTEND. <br /><br />

        THROUGH THIS ABOUT ONE YEAR I'VE BEEN INTERESTED
      </p>
    </div>
    <router-link to="/" class="backBtn">BACK</router-link>
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
