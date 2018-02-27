<template>
  <div>
    <button v-on:click="greet"> Greet</button>
    <br/>
    <span>The counter is {{ counter }}</span>
  </div>
</template>

<script>
export default {
  data () {
    return {
      name: "Vue"
    }
  },
  methods:{
    greet: function () {
      alert("Hello " + this.name)
    }
  }
}
</script>

<style>

</style>
