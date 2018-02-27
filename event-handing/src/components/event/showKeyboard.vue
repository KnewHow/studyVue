<template>
  <div>
    <label>Input</label>
    <input @keyup.up="up" />
  </div>

</template>

<script>
export default {
  data () {
    return {

    }
  },
  methods:{
    up: function () {
      console.log("up")
    }
  }
}
</script>
<style>

</style>
