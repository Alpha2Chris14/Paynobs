<template>
    <div class="stat_item">
            <img v-bind:src="img" v-bind:alt="alt">
            <div>
                <h6>{{head}}</h6>
                <p>{{amount}}</p>
            </div>
        </div>
</template>

<script>
export default {
  props: [
    'img',
    'alt',
    'head',
    'amount'
  ]
}
</script>

<style scoped>
 
</style>
