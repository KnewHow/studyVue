<template>
  <div id="demo3">
    <ul>
      <li v-for="(value) in obj">
        {{ value }}
      </li>
    </ul>

    <ul>
      <li v-for="(value,key) in obj">
        {{ key }} : {{ value }}
      </li>
    </ul>

    <ul>
      <li v-for="(value,key,index) in obj">
       {{ index }} : {{ key }} : {{ value }}
      </li>
    </ul>
  </div>
</template>

<script>
export default {
  data () {
    return {
      parentMessage: 'Parent',
      obj: {
        firstname: 'yuan',
        lastname: 'guohao',
        age: 23
      }
    }
  }
}
</script>

<style>

</style>
