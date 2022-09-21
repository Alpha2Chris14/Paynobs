<template>
  <div class="gift">
    <h2 class="display_2 color">Trade Your GiftCard</h2>
    <img src="../../assets/gift.png" alt="giftcard image" class="giftcard" />
    <p>
      At Paynobs we capitalize on the need of our customer. Seeing our customer
      make gain and profit so we offer the best rate for giftcard exchange.
    </p>
    <a href="" class="btn">Trade Now</a>
  </div>
</template>

<script>
export default {}
</script>

<style scoped>
.gift {
  padding-left: 5%;
  padding-right: 5%;
  padding-top: 40px;
  display: flex;
  flex-direction: column;
  align-items: center;
}
/* .color{
    color: #22be61 !important;
} */
.giftcard {
  width: 100% !important;
}

.gift p {
  width: 70%;
  text-align: center;
}

a {
  display: none;
}

@media screen and (min-width: 665px) {
  .gift {
    padding-left: 14%;
    padding-right: 14%;
    padding-top: 40px;
    /* display: flex;
        flex-direction: column;
        align-items: center; */

    display: grid;
    grid-template-columns: repeat(2, 1fr);
    grid-template-rows: repeat(3, 1fr);
  }

  .color {
    grid-row: 1/2;
    grid-column: 1/2;
    text-align: left;
    padding-bottom: 1px !important;
    padding-top: 1px !important;
  }

  .gift p {
    grid-row: 2/3;
    grid-column: 1/2;
    text-align: left;
    width: 400px;
  }

  .giftcard {
    grid-row: 1/-1;
    grid-column: 2/-1;
    width: 100% !important;
    height: auto !important; /*still in progress*/
  }

  a {
    display: flex;
    text-decoration: none;
  }
}
</style>
