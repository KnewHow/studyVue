<template>
  <div>
    <ul v-if="todos.length">
      <li v-for="todo in todos">
        {{ todo.name }}
      </li>
    </ul>
  </div>
</template>

<script>
export default {
  data () {
    return {
      todos: [
        {name: 'how'},
        {name: 'yison'}
      ]
    }
  }
}
</script>

<style>

</style>
