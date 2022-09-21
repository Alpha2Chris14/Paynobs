<template>
  <div id="app">
    <app-header />
    <Content />
  </div>
</template>

<script>
import Header from '../components/Header.vue'
import Content from '../components/Content.vue'
export default {
  name: 'App',
  components: {
    'app-header': Header,
    Content
  }
}
</script>

<style></style>
