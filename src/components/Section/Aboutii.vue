<template>
    <div class="who_group">
        <div class="who">
            <h2>Who We Are?</h2>
            <p>Paynobs is a company founded in 2020, dedicated to bringing the best of
                every daily activity closer to individuals.
                We are the best airtime to cash converter in Nigeria,
                 We offer the best rate for giftcard and crypto,
                 gives you a platform to pay your bills, top up your airtime,
                 purchase data subscription accross all network.
                 We offer economic growth to our customer thereby creating increasing
                 profit for you, so therefore you gain, we gain.
                 No more high cost data, no more mistaken excess airtime, no more high bills,
                 just you and paynobs.
            </p>
        </div>
        <img src="../../assets/girls.png" alt="" srcset="">
    </div>
</template>

<script>
export default {

}
</script>

<style scoped>
.who_group{
    display: flex;
    flex-direction: column;
    align-content: center;
    align-items: center;
}
.who{
    padding-left:8%;
    padding-right:8%;
    padding-top: 20px;
    display: flex;
    flex-direction: column;
    align-items: center;
}

.who h2{
    font-size:1.6rem;
    margin-bottom: 10px;
}

.who p{
    font-size:0.9rem;
    line-height: 1.2;
    text-align: center;
}

img{
    width: 100%;
    height: auto;
}

@media screen and (min-width: 765px) {
    /* .who_group{
        display: flex;
        flex-direction: row;
    } */
}

@media screen and (min-width: 1024px) {
    .who_group{
        display: flex;
        flex-direction: row;
        padding-left: 5%;
        padding-right: 5%;
    }

    .who{
        align-items: flex-start;
        width: 100%;
    }

    .who p{
        text-align: left;
        line-height: 1.5;
    }

    img{
        width: 50%;
        height: auto;
    }
}
</style>
