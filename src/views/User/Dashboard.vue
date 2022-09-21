<template>
    <div>
        <UserHeader/>
        <div class="content">
          <Introduction/>
          <Balance/>
          <Airtime/>
          <Giftcard/>
          <Bitcoin/>
          <Transaction/>
          <Statistic/>
        </div>
    </div>
</template>
<script>
import UserHeader from '../../components/Section/User/UserHeader.vue'
import Introduction from '../../components/Section/User/Introduction.vue'
import Balance from '../../components/Section/User/Balance.vue'
import Airtime from '../../components/Section/User/Airtime.vue'
import Giftcard from '../../components/Section/User/UserGiftcard.vue'
import Bitcoin from '../../components/Section/User/Bitcoin.vue'
import Transaction from '../../components/Section/User/Transaction.vue'
import Statistic from '../../components/Section/User/Statistic.vue'
export default {
  components: { UserHeader, Introduction, Balance, Airtime, Giftcard, Bitcoin, Transaction, Statistic }
}
</script>

<style scoped>
  .content{
    display: flex;
    flex-direction: column;
    align-items: center;
  }
</style>
