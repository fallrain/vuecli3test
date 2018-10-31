<template>
  <div>
    <span v-for="row in rows" @click="expend">{{row.path}}</span>
  </div>
</template>
<script>
  export default {
    props: ['rows'],
    methods: {
      expend() {

      }
    }
  }
</script>
<style>

</style>