<template>
  <div class="crypto_section">
    <h2 class="display_2 over">Trade Your Cryptocurrency with us</h2>
    <p>
      At Paynobs, we give the best value return for your gift card and crypto
      assets. We believe that everyone deserves the chance to profit, which
      drives us to help those who also believe this.
    </p>
    <a href="" class="btn">Register In Minute</a>
  </div>
</template>

<script>
export default {}
</script>

<style scoped>
.crypto_section {
  background: linear-gradient(rgba(0, 0, 0, 0.1), rgba(0, 0, 0, 0.6)),
    url("../../assets/womaanbtc.webp");
  background-size: cover;
  text-align: center;
  align-content: center;
  align-items: center;
  padding-left: 5%;
  padding-right: 5%;
  height: 100vh;
  background-repeat: no-repeat;
  background-position: center;
  color: white;
  display: flex;
  justify-content: center;
  flex-direction: column;
  background-attachment: fixed;
}

.over {
  width: 350px;
  padding-bottom: 15px !important;
}

a {
  text-decoration: none;
  align-self: center;
  margin-top: 15px !important;
}

@media screen and (min-width: 665px) {
  .display_2 {
    font-size: 2.5rem;
    width: 600px;
  }

  .crypto_section p {
    font-size: 1.2rem;
    width: 500px;
  }
}
</style>
