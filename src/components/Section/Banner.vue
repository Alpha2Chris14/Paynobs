<template>
  <div class="banner_group">
    <h1 class="display_1">Best Airtime To Cash Converter In Nigeria</h1>
    <p class="desc">
      We make it easy for you to convert your exccess airtime to cash, pay
      utility bills, buy airtime and data instantly.
    </p>
    <a class="btn">Get Started</a>

    <!-- <Illustration /> -->
  </div>
</template>

<script>
// import Illustration from "../assets/Illustration.vue";
export default {
  components: {
    //  Illustration
  }
}
</script>

<style>
.banner_group {
  padding-top: 100px;
  display: flex;
  flex-direction: column;
  /* justify-content: center; */
  padding-bottom: 20px;
}

.display_1 {
  font-size: 1.8rem;
  color: #22be61;
  margin-bottom: 20px;
  line-height: 1.2;
  width: 60%;
}

.desc {
  margin-bottom: 20px;
  font-size: 1rem;
  line-height: 1.2;
  /* color: rgb(46, 43, 43); */
  color: white;
  width: 60%;
}

.btn {
  background: #22be61;
  width: 150px;
  border-radius: 5px;
  height: 40px;
  color: white;
  font-size: 1rem;
  text-align: center;
  display: flex;
  align-items: center;
  justify-content: center;
  font-weight: bold;
  transition: all;
  transition-duration: 0.2s;
}

.btn:hover {
  cursor: pointer;
  color: #22be61;
  border: 2px solid #22be61;
  background: white;
  font-weight: 500;
  background: transparent;
}

@media screen and (min-width: 765px) {
  .banner_group {
    width: 80%;
    /* background: red; */
  }

  .display_1 {
    font-size: 2rem;
    width: 60%;
  }

  .desc {
    font-size: 1rem;
    width: 350px;
  }
}

@media screen and (min-width: 1024px) {
  .banner_group {
    width: 100%;
    display: flex;
    justify-content: center;
    align-items: center;
    text-align: center;
    height: 100%;
  }

  .display_1 {
    font-size: 3.5rem;
    width: 600px;
  }

  .desc {
    font-size: 1.2rem;
    width: 400px;
  }
}
</style>
