<template>
  <div>
    <span class="show-1"
          v-bind:class="{ show2:isShow2 }">看我的绑定的class
    </span>

    <span v-bind:class="classObj">
      我的class在内联
    </span>

    <span v-bind:class="[activeClass,errorClass]">
      lala
    </span>
  </div>
</template>

<script>
export default {
  data () {
    return {
      isShow2: true,
      classObj: {
        active: true,
        'text-danger': true,
        'how-front': false
      },
      activeClass: 'lala1',
      errorClass: 'lalal2',
    }
  }
}
</script>

<style>

</style>
