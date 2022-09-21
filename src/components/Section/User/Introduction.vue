<template>
    <div class="greet">
        <h1 class="salutation">Hello Christian,</h1>
        <p>Welcome to your Dashboard</p>
        <div class="action">
            <p>Quick action:</p>
            <a href="">Trade Bitcoin</a>
        </div>
    </div>
</template>

<script>
export default {}
</script>

<style scoped>
.greet{
    background: #22be601d;
    height: 180px;
    padding-left: 6%;
    padding-right: 6%;
    display: flex;
    flex-direction: column;
    justify-content:space-around;
    width:80%;
    border-radius: 10px;
    margin-top: 70px;
    box-shadow: 0 0 10px 10px rgba(247, 245, 245, 0.239);

}

.salutation{
    color: #22be61;
}
.greet p{
    font-size: 0.9rem;
    color: #121212;
}
.action{
    display: flex;
    align-content: space-between;
    justify-content: space-between;
}
.action p{
    align-self: center;
}
.action a{
    background: white;
    text-decoration: none;
    width: 50%;
    text-align: center;
    padding: 10px;
    border-radius: 50px;
    color: #22be61;
    border: 1px solid;
}

.action a:hover{
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
