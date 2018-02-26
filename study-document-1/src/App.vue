<template>
  <div id="app">
    <img src="./assets/logo.png">
    <p>{{ author }}</p>
    <firstcomponent></firstcomponent>
  </div>
</template>

<script>
import firstcomponent from './components/firstcomponent.vue'
export default {
  data () {
    return {
      author: 'How'
    }
  },
  components: {firstcomponent}
}
</script>

<style>

</style>
