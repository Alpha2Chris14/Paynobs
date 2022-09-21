<template>
    <header class="header">
        <DashLogo class="logo" setwidth="172" setheight="115"  />
        <div class="right_icon_menu">
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

</style>
