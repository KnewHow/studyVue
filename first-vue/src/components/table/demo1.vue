<template>
  <div>
    <ul>
      <li v-for="item in items">
        {{ item.message }}
      </li>
    </ul>
  </div>
</template>

<script>
export default {
  data () {
    return {
      items: [
        {message: 'Foo'},
        {message: 'Bar'}
      ]
    }
  }
}
</script>

<style>

</style>
