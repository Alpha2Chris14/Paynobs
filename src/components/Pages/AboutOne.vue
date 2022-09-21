<template>
    <div>
        <Aboutsection />
        <Aboutii/>
        <Gateway/>
        <Offers />
        <app-footer/>
    </div>
</template>

<script>
import Aboutsection from '../Section/Aboutsection.vue'
import Aboutii from '../Section/Aboutii.vue'
import Offers from '../Section/Offers.vue'
import Gateway from '../Section/Gateway.vue'
import Footer from '../Section/Footer.vue'
export default {
  components: { Aboutsection, Aboutii, Offers, Gateway, 'app-footer': Footer }
}
</script>
