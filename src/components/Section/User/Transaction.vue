<template>
    <div class="transaction">
        <h3>Recent Transactions</h3>
        <img src="../../../assets/no-transactions.svg" alt="no_transaction_svg"/>
        <h2>No Transaction</h2>
        <p>Your recent transaction will appear here, <a>Start a transaction</a></p>
    </div>
</template>
<script>

</script>
<style scoped>
.transaction{
        background: #fff;
        height: max-content;
        padding-top: 20px;
        padding-bottom: 20px;
        padding-left: 6%;
        padding-right: 6%;
        display: flex;
        gap: 20px;
        flex-direction: column;
        justify-content:space-around;
        align-content: stretch;
        width:80%;
        border-radius: 10px;
        margin-top: 30px;
        align-items: center;
        box-shadow: 0 0 10px 10px rgba(247, 245, 245, 0.771);
        color: #121212;
}

.transaction p{
    font-size: 0.7rem;
}

.transaction p a{
    font-size: 0.8rem;
    color: #22be61;
    font-weight: bold;
}

.transaction p a:hover{
    text-decoration: underline;
    cursor: pointer;
}
</style>
