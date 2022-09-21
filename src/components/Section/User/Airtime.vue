<template>
    <div class="airtime">
        <h3>Got Excess Airtime You Don't Need?</h3>
        <p>Trade it for cash now</p>
        <a href="">Convert Now</a>
    </div>
</template>

<script>
export default {
}
</script>

<style scoped>
    .airtime{
        background-color: #22be601d;
        background-image: url("../../../assets/airtime.svg");
        background-position: 100% 100%;
        background-repeat: no-repeat;
        width:80%;
        height: 150px;
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

    .airtime h3{
        font-size: 0.9rem;
    }

    .airtime p{
        font-size: 0.9rem;
        color: #121212;
    }

    .airtime a{
        background: white;
        text-decoration: none;
        width: 50%;
        text-align: center;
        padding: 10px;
        border-radius: 50px;
        color: #22be61;
        border: 1px solid;
    }

    .airtime a:hover{
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
