<template>
  <div class="content">
    <Overlay />
    <Offers />
    <Crypto />
    <GiftCard />
    <Recharge />
    <Feedback />
    <Gateway />
    <Subscribe />
    <app-footer />
  </div>
</template>

<script>
import Overlay from '../Section/Overlay.vue'
import Offers from '../Section/Offers.vue'
import Feedback from '../Section/Feedback.vue'
import Crypto from '../Section/Crypto.vue'
import Gateway from '../Section/Gateway.vue'
import Subscribe from '../Section/Subscribe.vue'
import Footer from '../Section/Footer.vue'
import GiftCard from '../Section/GiftCard.vue'
import Recharge from '../Section/Recharge.vue'

export default {
  components: {
    Overlay,
    Offers,
    Feedback,
    Crypto,
    Gateway,
    Subscribe,
    'app-footer': Footer,
    GiftCard,
    Recharge
  }
}
</script>

<style>
.group_section {
  padding-left: 5%;
  padding-right: 5%;
}
</style>
