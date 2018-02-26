<template>
  <div>
    <span v-if="ok">
      Yes
    </span>
    <span v-else="ok">
      No
    </span>
  </div>

</template>

<script>
export default {
  data () {
    return {
      ok: false
    }
  }
}
</script>


<style>

</style>
