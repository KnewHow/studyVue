<template>
  <div>
    <span v-bind:style="styleObj">
      innerstylebind
    </span>
  </div>
</template>

<script>
export default {
  data () {
    return {
      styleObj: {
        color: 'red',
        fontSize: '40px'
      }
    }
  }
}
</script>

<style>

</style>
