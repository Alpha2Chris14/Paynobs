<template>
    <div class="giftcard">
        <div class="content">
            <img src="../../../assets/giftcard.png" alt="gift_img">
            <p>Paynobs offers you the best rate for gift card exchange. Any card you got
                we got you covered.
            </p>
            <a href="">Trade Now</a>
        </div>
    </div>
</template>

<script>
export default {}
</script>

<style scoped>
    .giftcard{
        height: max-content;
        background-color: rgb(237, 237, 237);
        padding-left: 6%;
        padding-right: 6%;
        display: flex;
        gap:20px;
        flex-direction: column;
        justify-content:end;
        width:80%;
        border-radius: 10px;
        margin-top: 50px;
        box-shadow: 0 0 10px 10px rgba(247, 245, 245, 0.239);
    }

    img{
        width: 50%;
        height: auto;
    }

    .content{
        display: flex;
        flex-direction: column;
        gap: 15px;
        align-items: center;
        padding-top: 20px;
        padding-bottom: 20px;
    }

    .content p{
        color:#121212;
        font-size: 0.95rem;
        text-align: center;
    }

    .content a{
        text-decoration: none;
        width: 50%;
        text-align: center;
        padding: 10px;
        border-radius: 50px;
        color: #22be61;
        border: 1px solid;
    }

    .content a:hover{
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
