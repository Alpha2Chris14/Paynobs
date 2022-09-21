<template>
  <div class="recharge">
    <div class="rech_desc">
      <h2 class="display_2 air">Airtime & Data Subscription</h2>
      <p class="rex_des">
        With Paynobs you always get the best rates and prices on everything from
        airtime and data transactions and even your bill payments
      </p>
    </div>
    <img src="../../assets/rec.png" alt="recharge" class="rec" srcset="" />
  </div>
</template>

<script>
export default {}
</script>

<style>
.recharge {
  background-color: #22be61;
  display: flex;
  padding-left: 5%;
  padding-right: 5%;
  flex-direction: column;
  color: white;
  margin-top: 20px;
}

.recharge p {
  text-align: center;
}
.rec {
  height: auto;
  width: 100%;
}

@media screen and (min-width: 665px) {
  .recharge {
    display: grid;
    grid-template-columns: repeat(2, 1fr);
    padding-left: 10%;
    padding-right: 10%;
  }

  .rech_desc {
    align-self: center;
    /* background: red; */
    display: flex;
    flex-direction: column;
    justify-content: space-around;
    grid-column: 2/-1;
    grid-row: 1/-1;
    height: 50%;
  }

  .recharge p {
    text-align: left !important;
  }

  .air {
    text-align: left;
    padding: 0;
  }

  .recharge img {
    grid-row: 1/-1;
    grid-column: 1/2;
    width: 80% !important;
    height: auto !important; /*still in progress*/
  }
}
</style>
