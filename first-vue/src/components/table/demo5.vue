<template>
  <div>
    <template v-for="item in items">
      <li>
        {{ item.name }}
      </li>
    </template>
  </div>
</template>

<script>
export default {
  data () {
    return {
      items: [
        {name: '123'},
        {name: '456'}
      ]
    }
  }
}
</script>

<style>

</style>
