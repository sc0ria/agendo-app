<template>
  <div>
    <h1>Añadir Agenda</h1>
    <todo-form />
  </div>
</template>

<script>
export default {
  name: 'CreateTodo',
  layout: 'action',
  middleware: 'auth',
}
</script>

<style scoped>
.box-card {
  width: 750px;
  padding: 10;
  margin-bottom: 10px;
}

.center {
  text-align: center;
}
</style>