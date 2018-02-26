<template>
  <div id="app">
    <div>
      <img src="./assets/logo.png">
    </div>
    <div>
      <div :class="separator">--------------Class and style bind-------------------</div>
      <span>{{ msg }}</span>
      <firstcomponent></firstcomponent>
      <watchdemocomponent></watchdemocomponent>
      <bindstylecomponent></bindstylecomponent>
      <singlecomponent v-bind:class="singleObject"></singlecomponent>
      <innerstylebind></innerstylebind>
    </div>

    <div>
      <div>--------------Class and style bind-------------------</div>
    </div>


  </div>
</template>

<script>
import firstcomponent from './components/firstcomponent.vue'
import watchdemocomponent from './components/watchdemocomponent.vue'
import bindstylecomponent from './components/bindstylecomponent.vue'
import singlecomponent from './components/singlecomponent.vue'
import innerstylebind from './components/innerstylebind.vue'
export default {
  data () {
    return {
      msg: "hello vue",
      singleObject: {
        activeClass: 'active',
        errorClass: 'danger-show'
      },
      separator:'separator'
    }
  },
  components: {
    firstcomponent,
    watchdemocomponent,
    bindstylecomponent,
    singlecomponent,
    innerstylebind
  }
}
</script>

<style>
.separator{
  color:black;
}
</style>
