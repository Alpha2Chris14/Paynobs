<template>
  <div class="gateway_con">
    <div>
      <h2 class="display_2 mod">Your Gateway To Crypto</h2>
      <p>
        More than creating a seamless platform for you to perform crypto
        transactions, we are with you every step of the way, providing you with
        tips and tricks to becoming a crypto guru.
      </p>
    </div>
  </div>
</template>

<script>
export default {}
</script>

<style scoped>
.gateway_con {
  background-color: #22be61;
  background-image: url("../../assets/rocket.svg"),
    url("../../assets/strips.svg");
  background-repeat: no-repeat;
  background-position: 0, 100%, 100%, 100%;
  background-size: auto 40%, auto 60%;
  background-position-y: bottom;
  height: 60vh;
}

.gateway_con div {
  display: flex;
  flex-direction: column;
  padding-left: 5%;
  padding-right: 5%;
  height: 100%;
  color: white;
}

.gateway_con p {
  font-size: 14px;
  text-align: center;
}

@media screen and (min-width: 665px) {
  .gateway_con {
    padding-left: 10%;
    padding-right: 10%;
    height: 40vh;
    background-size: auto 100%, auto 100%;
  }

  .gateway_con p {
    width: 500px;
  }

  .gateway_con div {
    justify-content: center;
    align-items: center;
  }
}
</style>
