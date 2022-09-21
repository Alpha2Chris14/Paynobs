<template>
  <div class="subscribe">
    <h2 class="display_2 over">Subcribe to our news letter</h2>
    <p>
      Get notified of all our premium discounts and promos. We will also notify
      you from time to time when we make updates to serve you better.
    </p>
    <div class="sub_group">
      <input type="email" placeholder="youremail@email.com" />
      <button>Subscribe</button>
    </div>
  </div>
</template>

<script>
export default {}
</script>

<style>
.subscribe {
  padding-left: 5%;
  padding-right: 5%;
  height: 280px;
  display: flex;
  flex-direction: column;
  align-items: center;
}
.over {
  padding-bottom: 15px !important;
}
.subscribe p {
  width: 70%;
  text-align: center;
  line-height: 1.2;
  font-size: 0.95rem;
  padding-bottom: 15px;
}
.sub_group {
  display: flex;
  width: 70%;
  justify-content: center;
}

.sub_group input {
  outline: none;
  border: 2px solid #22be61;
  height: 40px;
  width: 100%;
  color: #22be61;
  border-top-left-radius: 5px;
  border-bottom-left-radius: 5px;
  padding-left: 1%;
}

.sub_group button {
  color: white;
  outline: none;
  border: none;
  background: #22be61;
  width: 30%;
  border-top-right-radius: 5px;
  border-bottom-right-radius: 5px;
}

@media screen and (min-width: 665px) {
  .subscribe {
    padding-left: 10%;
    padding-right: 10%;
    height: 300px;
    justify-content: center;
  }

  .subscribe p {
    width: 500px;
    text-align: center;
  }

  .sub_group input {
    width: 400px;
  }

  .sub_group button {
    width: 100px;
  }

  .sub_group button:hover {
    cursor: pointer;
  }
}
</style>
