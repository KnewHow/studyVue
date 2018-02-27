<template>
  <div>
    <button v-on:click="counter +=  1"> Add</button>
    <br/>
    <span>The counter is {{ counter }}</span>
  </div>
</template>

<script>
export default {
  data () {
    return {
      counter: 0
    }
  }
}
</script>

<style>

</style>
