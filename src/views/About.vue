<template>
  <div>
    <app-header />
    <AboutOne/>
  </div>
</template>

<script>
import Header from '../components/Header.vue'
import AboutOne from '../components/Pages/AboutOne.vue'
export default {
  components: {
    'app-header': Header,
    AboutOne
  }
}
</script>

<style></style>
