<template>
  <div>
    <img alt="Vue logo" src="./assets/logo.png" />
    <Todo />
  </div>
</template>

<script>
import Todo from './components/Todo.vue'

export default {
  name: 'App',
  components: {
    Todo
  }
}
</script>

