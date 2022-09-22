<template>
    <div class="statistics">
        <div class="stat_item">
            <img src="../../../assets/pending-trans.85892e13.svg" alt="pending_transaction">
            <div>
                <h6>PENDING TRANSACTIONS</h6>
                <p>0</p>
            </div>
        </div>

        <div class="stat_item">
            <img src="../../../assets/paid-trans.e1742ee8.svg" alt="paid_transaction">
            <div>
                <h6>PAID TRANSACTIONS</h6>
                <p>0</p>
            </div>
        </div>

        <div class="stat_item">
            <img src="../../../assets/declined-trans.4be695cf.svg" alt="declined_transaction">
            <div>
                <h6>DECLINED TRANSACTIONS</h6>
                <p>0</p>
            </div>
        </div>

        <div class="stat_item">
            <img src="../../../assets/wallet-stat.5bec86c9.svg" alt="amount_in_wallet">
            <div>
                <h6>Amount In Wallet</h6>
                <p>₦0.00</p>
            </div>
        </div>
    </div>
</template>
<script>
export default {
}
</script>

<style scoped>
    .statistics{
        background: #fff;
        height: auto;
        padding-left: 6%;
        padding-right: 6%;
        display: flex;
        flex-direction: column;
        justify-content:space-around;
        align-content:space-between;
        width:80%;
        border-radius: 10px;
        margin-top: 30px;
        box-shadow: 0 0 10px 10px rgba(247, 245, 245, 0.771);
        padding-top: 40px;
        padding-bottom: 20px;
        color: #121212;
        margin-bottom: 20px;
    }

    .stat_item{
        display:flex;
        gap:12px;
        margin-bottom: 20px;
    }

    .stat_item div{
        height: 100%;
        display: flex;
        flex-direction: column;
        justify-content: space-evenly;
        justify-self: center;
    }

    .stat_item div p{
        font-weight: bold;
        font-size: 1.8rem;
    }
</style>
