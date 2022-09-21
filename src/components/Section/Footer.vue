<template>
  <footer>
    <div class="footer">
      <div class="know">
        <p>
          <b>Paynobs</b> is a company dedicated to bringing solutions closer to
          reach of everyday individuals. By carving and staying in the niche of
          quality service and top notch customer care, we have grown from being
          just 'Nigeria's Best Airtime To Cash Converter' to being more.
          Bringing you the services you need the most such as Bill Payments and
          ground breaking affordable Data Topup plans in the best way possible
          to serve the best customers available.
        </p>
      </div>
      <div class="customer phone">
        <h5>Customer care phone number</h5>
        <p>+234 9060652190</p>
      </div>
      <div class="customer follow">
        <h5>Follow Us</h5>
        <div></div>
      </div>

      <div class="customer address">
        <h5>Office Address</h5>
        <p>No 5 Kolawale Street, Ikeja Along,Lagos</p>
      </div>

      <div class="customer mail">
        <h5>Email Support</h5>
        <p>support@paynobs.com</p>
      </div>

      <div class="customer get">
        <h5>Get Mobile App</h5>
        <div class="app_item">
          <img src="../../assets/playstore.png" alt="" srcset="" />
          <img src="../../assets/apple.png" alt="" srcset="" />
        </div>
      </div>
      <div class="customer others">
        <a>Trade Giftcard</a>
        <a>Convert Airtime</a>
        <a>Buy Airtime</a>
        <a>Bill Payments</a>
        <a>Buy Data</a>
      </div>
      <hr class="line" />

      <div class="customer">
        <a>Terms And Condition</a>
        <a>Privacy Policy</a>
        <a>FAQs</a>
      </div>
    </div>

    <div class="last">
      <p>© 2020 Paynobs Technologies. All Rights Reserved</p>
    </div>
  </footer>
</template>

<script>
export default {}
</script>
<style>
.footer {
  background: #22be61;
  display: flex;
  padding-left: 5%;
  padding-right: 5%;
  color: #fff;
  padding-top: 20px;
  line-height: 1.2;
  flex-direction: column;
}

footer .know {
  font-size: 0.9rem;
  padding-bottom: 20px;
}

.customer {
  margin-bottom: 20px;
  display: flex;
  flex-direction: column;
}

.customer > h5 {
  padding-bottom: 10px;
}
.customer > a {
  margin-bottom: 10px;
}

.customer > a:hover {
  text-decoration: underline;
  cursor: pointer;
}
.line {
  margin-bottom: 20px;
}
.last {
  width: 100%;
  text-align: center;
  background: rgb(14, 14, 14);
  color: #22be61;
  height: 80px;
  display: flex;
  flex-direction: column;
  justify-content: center;
}

.app_item {
  display: flex;
  gap: 5px;
}

.app_item img {
  border: 2px solid rgb(34, 30, 31);
  height: 75%;
  width: 40%;
  border-radius: 10px;
  filter: invert();
  padding-left: 2%;
  padding-right: 2%;
}

.app_item img:hover {
  filter: none;
}

@media screen and (min-width: 980px) {
  .footer {
    padding-left: 10%;
    padding-right: 10%;
    widows: 100%;
    display: grid;
    grid-template-rows: 100px 1fr 2px;
    grid-template-columns: repeat(4, 1fr);
    gap: 10px;
  }

  .phone {
    grid-column: 1/2;
    grid-row: 1/2;
  }

  .follow {
    grid-column: 2/3;
    grid-row: 1/2;
  }

  .address {
    grid-column: 3/4;
    grid-row: 1/2;
  }

  .mail {
    grid-column: 4/-1;
    grid-row: 1/2;
  }

  .know {
    grid-row: 2/3;
    grid-column: 1/3;
  }

  .get {
    grid-row: 2/3;
    grid-column: 3/4;
  }

  .line {
    grid-row: 3/4;
    grid-column: 1/-1;
    height: 1px;
    outline: none;
    border: none;
    border-top: 1px solid white;
  }
}
</style>
