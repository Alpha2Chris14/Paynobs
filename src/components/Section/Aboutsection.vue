<template>
    <div class="about">
        <div class="about_one">
            <p class="desc">Hi Chief</p>
            <h1 class="display_about_1">We Are Paynobs</h1>
            <p class="desc abs">
                Want to convert your excess airtime? Paynobs offers the best rate for airtime conversion
                , airtime topup and bills payment
            </p>
        </div>
    </div>
</template>

<!-- <script>
    export default{

    }
</script> -->

<style>
    .about{
        background: linear-gradient(rgba(0, 0, 0, 0.6), rgba(0, 0, 0, 0.6)),
    url("../../assets/about.jpg");
  background-size: cover;
  background-blend-mode: darken;
        height: auto;
        padding-top: 60px;
        padding-left: 10%;
        padding-right: 10%;
        display: flex;
        align-items: center;
    }
    .about_one{
        color: white;
        width: 100%;
        padding-top: 30px;
        display: flex;
        padding-bottom: 20px;
        flex-direction: column;
    }

    .display_about_1{
        color: #22be61;
        margin-bottom: 20px;
        line-height: 1.2;
        font-size: 1.8rem;
        width: 80%;
    }

    .abs{
        width: 80%;
    }

    img{
        width: 50%;
    }

    @media screen and (min-width: 765px) {
        .display_about_1{
            font-size: 2rem;
            width: 60%;
        }
    }

    @media screen and (min-width: 1024px) {
    .about {
        width: 100%;
        display: flex;
        height: 100vh;
        padding-left: 12%;
        padding-right: 12%;
    }

    .display_about_1 {
        font-size: 3.5rem;
        width: 600px;
    }

    .abs{
        width: 450px;
    }
}
</style>
