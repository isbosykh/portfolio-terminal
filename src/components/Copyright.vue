<template>
  <div>
    <a @click="$router.go(-1)" class="backBtn">BACK</a>
    <span>(C) COPYRIGHT HACK_WASHINGTON INC. 1980-2077.</span>
  </div>
</template>

<script>
export default {
  name: "Copyright"
};
</script>

<style lang="scss" scoped>
div {
  position: absolute;
  right: 0;
  bottom: 0;
  margin: 10px;
}
span {
  display: block;
  font-size: 1rem;
  text-align: right;
}
.backBtn {
  display: block;
  text-align: right;
  margin: 2rem;
  font-size: 2rem;
}
</style>
