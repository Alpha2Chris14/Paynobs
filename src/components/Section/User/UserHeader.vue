<template>
    <header class="header">
        <DashLogo class="logo" setwidth="172" setheight="115"  />
        <nav id="side_menu" ref="menu">
          <div class="item">Dashboard</div>
          <div class="item">Transaction</div>
          <div class="item">Wallet</div>
          <div class="item">Setting</div>
          <div class="item">Logout</div>
        </nav>
        <div class="right_icon_menu" v-on:click="toggle">
            <div class="menu-mobile">
                <div class="bar"></div>
                <div class="bar"></div>
                <div class="bar"></div>
            </div>
        </div>
    </header>
</template>

<script>
import DashLogo from '../../assets/DashLogo.vue'
export default {
  components: {
    DashLogo
  },
  data () {
    return {
      show: false
    }
  },

  methods: {
    toggle: function () {
      const mobilemenu = document.getElementById(this.$refs.menu.id)
      if (this.show) {
        mobilemenu.style.transition = 'all'
        mobilemenu.style.transitionDuration = '1s'
        mobilemenu.style.transform = 'translateX(240px)'
        this.show = !this.show
        return
      }
      mobilemenu.style.transition = 'all'
      mobilemenu.style.transitionDuration = '1s'
      mobilemenu.style.transform = 'translateX(-120px)'
      this.show = !this.show
    }
  }
}
</script>

<style scoped>
    .header {
    width: 100%;
    display: flex;
    background: #fff;
    height: 60px;
    align-items: center;
    justify-content: space-between;
    padding-left: 1%;
    padding-right: 1%;
    position: fixed;
    z-index: 1;
    top: 0;
    box-shadow: 0 4px 13px rgb(0 0 0 / 5%);
    /* 121212 */
}

.right_icon_menu {
  display: grid;
  gap: 12%;
  grid-template-columns: repeat(2, 1fr);
  align-items: center;
}

.menu-mobile {
  display: grid;
  grid-template-rows: repeat(3, 1fr);
  width: 25px;
  height: 20px;
}

.bar {
  display: block;
  background-color:  #22be61;
  width: 100%;
  height: 2px;
  align-self: center;
}

#side_menu{
  background:  #fff;
  box-shadow: 0 32px 20px 5px rgba(168, 168, 168,0.6);
  height: 100vh;
  position:absolute;
  width:240px;
  top:60px;
  left: -240px;
  display: flex;
  flex-direction: column;
  align-items: center;
  padding-top: 50px;
  gap: 50px;
}

.item{
  width: 70%;
  height: 70px;
  text-align: center;
  font-size: 1.2rem;
  display: flex;
  align-items: center;
  justify-content: center;
}

.item:hover{
  background: white;
  cursor: pointer;
  box-shadow: 0 0 20px 5px rgba(168, 168, 168,0.6);
  border-radius: 5px;
}

</style>
