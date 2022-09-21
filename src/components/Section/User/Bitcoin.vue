<template>
    <div class="crypto">
        <img src="../../../assets/crypto.png" alt="crypto_coins">
        <a href="">Trade Crypto Now</a>
    </div>
</template>

<script>
export default {

}
</script>

<style scoped>
    .crypto{
        background: #fff;
        height: max-content;
        padding-left: 6%;
        padding-right: 6%;
        padding-top: 20px;
        padding-bottom: 20px;
        display: flex;
        flex-direction: column;
        justify-content:space-around;
        width:80%;
        border-radius: 10px;
        margin-top: 30px;
        align-items: center;
        box-shadow: 0 0 10px 10px rgba(247, 245, 245, 0.771);
    }

    img{
        width:100%;
        height: auto;
    }

    .crypto a{
        text-decoration: none;
        width: 50%;
        text-align: center;
        padding: 10px;
        border-radius: 50px;
        color: #22be61;
        border: 1px solid;
    }

    .crypto a:hover{
        color: white;
        text-decoration: none;
        width: 50%;
        text-align: center;
        padding: 10px;
        border-radius: 50px;
        background: #22be61;
        border: 1px solid;
    }
</style>
