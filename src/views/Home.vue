<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/logo.png" class="logo" />
    <todo-list></todo-list>
  </div>
</template>

<script>
import TodoList from "@/components/TodoList.vue";

export default {
  name: "Home",
  components: {
    TodoList
  }
};
</script>

<style scoped>
.logo {
  display: block;
  margin: 20px auto;
  height: 75px;
}
</style>
