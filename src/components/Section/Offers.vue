<template>
  <div class="group_con">
    <h2 class="display_2">Why use our platform?</h2>
    <div class="group">
      <div class="offer_con">
        <img
          src="../../assets/mobile-payment-svgrepo-com.svg"
          alt=""
          srcset=""
        />
        <h4>Best and cheapest rates</h4>
        <p>
          Our platform is built on the best data security networks with absolute
          care to make sure your experience is simple and seamless.
        </p>
      </div>

      <div class="offer_con">
        <img src="../../assets/lock-svgrepo-com.svg" alt="" srcset="" />
        <h4>Secure and easy-to-use</h4>
        <p>
          Our platform is built on the best data security networks with absolute
          care to make sure your experience is simple and seamless.
        </p>
      </div>

      <div class="offer_con">
        <img
          src="../../assets/payment-method-svgrepo-com.svg"
          alt=""
          srcset=""
        />
        <h4>Pay Bills at lowest cost posible</h4>
        <p>
          Our platform is built on the best data security networks with absolute
          care to make sure your experience is simple and seamless.
        </p>
      </div>

      <div class="offer_con">
        <img src="../../assets/convertio-svgrepo-com.svg" alt="" srcset="" />
        <h4>Convert Your Airtime To Cash</h4>
        <p>
          Our platform is built on the best data security networks with absolute
          care to make sure your experience is simple and seamless.
        </p>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  components: {}
}
</script>

<style scoped>
img {
  width: 50px;
  /* width: 35px; */
  height: auto;
}
</style>
<style>
.group_con {
  background: rgb(254, 251, 251, 0.9);
}
.display_2 {
  text-align: center;
  padding-top: 40px;
  padding-bottom: 30px;
  font-size: 1.5rem;
}
.group {
  display: grid;
  /* grid-template-columns: repeat(2,1fr); */
  grid-template-rows: repeat(4, 1fr);
}
.offer_con {
  display: flex;
  flex-direction: column;
  align-content: center;
  justify-content: center;
  align-items: center;
  gap: 20px;
  text-align: center;
  padding: 20px;
}

.offer_con h4 {
  font-size: 1rem;
}

.offer_con p {
  font-size: 0.9rem;
  width: 70%;
  font-weight: 200;
  line-height: 1.2;
}

@media screen and (min-width: 765px) {
  .group {
    display: grid;
    grid-template-columns: repeat(2, 1fr);
    grid-template-rows: repeat(2, 1fr);
  }
}
@media screen and (min-width: 1044px) {
  .group_con {
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    padding-left: 5%;
    padding-right: 5%;
  }
  .display_2 {
    text-align: center;
    padding-top: 40px;
    padding-bottom: 30px;
    font-size: 2.5rem;
  }

  .group {
    display: grid;
    grid-template-columns: repeat(4, 1fr);
    /* grid-template-rows: repeat(2, 1fr); */
    height: 280px;
  }

  .offer_con h4 {
    font-size: 1rem;
  }

  .offer_con p {
    font-size: 0.95rem;
    width: 100%;
    font-weight: 200;
    line-height: 1.4;
    word-wrap: break-word;
  }
  img {
    width: 60px;
    /* width: 35px; */
    height: auto;
  }
}
</style>
