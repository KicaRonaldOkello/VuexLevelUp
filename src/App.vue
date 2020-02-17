<template>
  <div id="app">
    <div class="container">
      <AddTodo />
      <FilterToDos />
      <Todos />
    </div>
  </div>
</template>

<script>
import Todos from './components/ToDo.vue'
import AddTodo from './components/AddTodo'
import FilterToDos from './components/FilterToDos'

export default {
  name: 'App',
  components: {
    Todos,
    AddTodo,
    FilterToDos
  }
}
</script>

<style>
body {
  font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
  line-height: 1.6;
  background: #e8f7f0;
}

.container {
  max-width: 1100px;
  margin: auto;
  overflow: auto;
  padding: 0 2rem;
}

</style>
