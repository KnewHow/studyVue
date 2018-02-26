<template>
  <div>
    <p>
      Ask a question:
      <input v-model="question">
    </p>

    <p>
      {{ answer }}
    </p>
  </div>
</template>

<script>
export default {
  data () {
    return {
      question: '',
      answer: 'I can not give your answer'
    }
  },
  watch: {
    question:function () {
      this.answer = 'Waiting for you to stop typing...'
      this.getAnswer()
    }
  },
  methods: {
    getAnswer:function () {
      console.log('lala')
    }
  }
}
</script>

<style>

</style>
