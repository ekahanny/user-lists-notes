<template>
  <div class="todo-app">
    <h1>To Do List</h1>
    <TodoForm />
    <TodoList />
  </div>
</template>

<script>
import { defineComponent } from 'vue'
import TodoForm from './components/TodoForm.vue'
import TodoList from './components/TodoList.vue'
export default defineComponent({
  components: { TodoForm, TodoList },
  setup() {
    return {}
  }
})
</script>
<style scoped>
.todo-app {
  padding: 5vh;
  min-height: 100vh;
  width: 30vw;
  background-color: #f7f9fc;
}
</style>
