<template>
    <div class="balance">
        <h2 class="head">Balance</h2>
        <p>₦350000.00</p>
    </div>
</template>

<script>
export default {
}
</script>

<style>
    .balance{
        background: #fff;
        height: 100px;
        padding-left: 6%;
        padding-right: 6%;
        display: flex;
        flex-direction: column;
        justify-content:space-around;
        width:80%;
        border-radius: 10px;
        margin-top: 30px;
        box-shadow: 0 0 10px 10px rgba(247, 245, 245, 0.771);
    }
    .head{
        font-size:.9rem;
    }

    .balance p{
        font-size:1.5rem;
        color: #22be61;
    }
</style>
