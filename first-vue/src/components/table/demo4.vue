<template>
  <div>

    <div>
      <ul>
        <li v-for="n in eventNumbers">
          {{ n }}
        </li>
      </ul>
    </div>

    <div>
      <span v-for="n in 10">
        {{ n }}
      </span>
    </div>

  </div>
</template>
  <script>
  export default {
    data () {
      return {
        number: [1,2,3,4,5,6]
      }
    },
    computed: {
      eventNumbers: function (){
        return this.number.filter(function (number) {
          return number % 2 === 0
        })
      }
    }
  }
  </script>

  <style>

  </style>
