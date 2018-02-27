<template>
  <div id="app">
    <img src="./assets/logo.png">
    <div>
      <div>------------event handing------------</div>
      <demo1></demo1>
      <demo2></demo2>
      <showKeyboard></showKeyboard>
    </div>
  </div>

</template>

<script>
import demo1 from './components/event/demo1.vue'
import demo2 from './components/event/demo2.vue'
import showKeyboard from './components/event/showKeyboard.vue'
export default {
  name: 'App',
  components: {
    demo1,
    demo2,
    showKeyboard
  }
}
</script>

<style>

</style>
