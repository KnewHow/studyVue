<template>
  <div id="app-2">
    lala
    {{ msg }}
    <firstcomponent></firstcomponent>
    <secondcomponet></secondcomponet>
  </div>

</template>

<script>
import firstcomponent from './component/firstcomponent.vue'
export default{
  data () {
    return {
      msg: 'Hello Vue!'
    }
  },
  components: {firstcomponent}
}

</script>

<style lang="scss">

</style>
