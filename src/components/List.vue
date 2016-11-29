<template lang="html">
  <div class="test-1">
    <h1 class="heading">{{ msg }}</h1>
    <div class="input-box">
      <input type="text" name="tasks" placeholder="I need to..."></input>
      <button>Add the task!</button>
    </div>
    <ul class="todos">
      <li v-for="todo in todos">
        <span class="todo-list-item">{{ todo.thing }}</span>
      </li>
    </ul>
  </div>
</template>

<script>
export default {
  name: 'list',
  data () {
    return {
      msg: 'Enter, edit, or delete the tasks you need to!',
      todos: [
        { thing: 'Get familiar with the scaffolding in Vue/Webpack' },
        { thing: '???' },
        { thing: 'Profit' }
      ]
    }
  }
}
</script>

<style scoped>

.heading {
  color: red;
}

.todos {
  list-style: none;
}

.todo-list-item {
  color: blue;
}

</style>
