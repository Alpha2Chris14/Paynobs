<template>
  <header ref="header" id="menu_header">
    <Logo class="logo" setwidth="172" setheight="115" />
    <ul ref="nav" id="nav_bar">
      <li><a href=""><router-link to="/about">About Us</router-link></a></li>
      <li class="product" v-on:click="toggleSub">
        <a>Product</a>
        <ul class="sub_product" id="sub" ref="sub_menu">
          <li>Convert Airtime</li>
          <li>Buy Airtime</li>
          <li>Buy Data</li>
          <li>Pay A Bill</li>
          <li>Trade Crypto</li>
          <li>Trade Giftcard</li>
        </ul>
      </li>
      <li><a href="">Blog</a></li>
      <li><a href="">FAQs</a></li>
      <li><a href="">Contact Us</a></li>
      <li class="login_con"><a href="" class="download">Download app</a></li>
      <li class="login_con"><a href="" class="login">Login</a></li>
    </ul>
    <div class="right_icon_menu" v-on:click="toggle">
      <div class="menu-mobile">
        <div class="bar"></div>
        <div class="bar"></div>
      </div>
    </div>
  </header>
</template>

<script>
import Logo from './assets/Logo.vue'
export default {
  components: {
    Logo
  },

  data () {
    return {
      show: false,
      showSub: false
    }
  },

  methods: {
    toggle: function () {
      this.show = !this.show
      const id = this.$refs.nav.id
      const nav = document.getElementById(id)
      nav.style.transition = 'all'
      nav.style.transitionDuration = '0.8s'
      if (this.show) {
        nav.style.transform = 'translateY(0px)'
      } else {
        nav.style.transform = 'translateY(-560px)'
      }
    },
    toggleSub: function () {
      this.showSub = !this.showSub
      console.log(this.$refs)
      const id = this.$refs.sub_menu.id
      const navSub = document.getElementById(id)
      if (this.showSub) {
        navSub.style.display = 'flex'
      } else {
        navSub.style.display = 'none'
      }
    }
  }
}
</script>

<style scoped>
header {
  width: 100%;
  display: flex;
  background: rgba(0, 0, 0, 0.3);
  height: 60px;
  box-shadow: 0 4px 13px rgb(0 0 0 / 5%);
  align-items: center;
  justify-content: space-between;
  padding-left: 3%;
  padding-right: 3%;
  position: fixed;
  z-index: 1;
  top: 0;
}

ul {
  position: absolute;
  display: flex;
  flex-direction: column;
  background: rgba(0, 0, 0, 0.9);
  box-shadow: 0 4px 13px rgb(0 0 0 / 5%);
  width: 100%;
  left: 0;
  top: 60px;
  text-align: center;
  justify-content: space-around;
  height: 500px;
  font-weight: bold;
  transform: translateY(-560px);
  z-index: -10;
}

ul li:hover {
  cursor: pointer;
}
ul a {
  color: #22be61;
  text-decoration: none;
}

.product{
  position: relative;
  display: inline-block;
}

.sub_product{
  position: absolute;
  color: #22be61;
  display: none;
  flex-direction: column;
  background: rgba(0, 0, 0, 0.5);
  box-shadow: 0 4px 13px rgb(0 0 0 / 5%);
  top: 37px;
  z-index: 20;
  width:100px;
  left:-27px;
}

.sub_product li{
  list-style-type: none;
  margin-top: 20px;
  margin-bottom: 10px;
}

.login_con {
  width: 100%;
  display: flex;
  justify-content: center;
  justify-items: center;
}
.login {
  color: white;
  background: #22be61;
  width: 130px;
  display: block;
  padding: 12px;
  border-radius: 5px;
  transition: all;
  transition-duration: 0.2s;
}
.login:hover {
  cursor: pointer;
  border: 2px solid #22be61;
  background: none;
  color: #22be61;
}

.download {
  border: 2px solid #22be61;
  background: none;
  color: #22be61;
  width: auto;
  display: block;
  padding: 12px;
  border-radius: 5px;
  transition: all;
  transition-duration: 0.2s;
}

.download:hover {
  color: white;
  background: #22be61;
  cursor: pointer;
}
.right_icon_menu {
  display: grid;
  gap: 12%;
  grid-template-columns: repeat(2, 1fr);
  align-items: center;
}

.menu-mobile {
  display: grid;
  grid-template-rows: repeat(2, 1fr);
  width: 20px;
  height: 20px;
}

.right_icon_menu {
  display: grid;
  grid-template-columns: repeat(2, 1fr);
}
.bar {
  display: block;
  background-color: #22be61;
  width: 100%;
  height: 2px;
  align-self: center;
}

@media screen and (min-width: 1024px) {
  header {
    padding-left: 10%;
    padding-right: 10%;
  }

  .right_icon_menu {
    display: none;
  }

  ul {
    position: relative;
    display: flex;
    flex-direction: row;
    background: none;
    box-shadow: none;
    width: 100%;
    left: 0;
    top: 0px;
    text-align: center;
    justify-content: space-around;
    height: 0px;
    font-weight: bold;
    transform: none !important;
    z-index: none;
    height: auto;
    align-items: center;
    font-size: 13px;
  }

  ul li {
    list-style-type: none;
  }

  .login_con {
    width: auto;
  }

  li:not(.login_con):hover {
    border-bottom: 3px solid #22be61;
  }
}
</style>
