<template>
  <div class="content">
    <Banner />
  </div>
</template>

<script>
import Banner from '../Section/Banner.vue'

export default {
  components: { Banner }
}
</script>

<style scoped>
.content {
  padding-left: 5%;
  padding-right: 5%;
  background: linear-gradient(rgba(0, 0, 0, 0.6), rgba(0, 0, 0, 0.6)),
    url("../../assets/backii.jpg");
  background-size: cover;
  background-blend-mode: darken;
  background-repeat: no-repeat;
  background-attachment: scroll;
  height: auto;
  /* HEllo */
}

/* .background{
  position: absolute;
  background: black;
  width: 100%;
  height: 323px;
  left:0;
  opacity:0.2;
} */

@media screen and (min-width: 1024px) {
  .content {
    padding-left: 20%;
    padding-right: 20%;
    height: 100vh;
  }
}
</style>
