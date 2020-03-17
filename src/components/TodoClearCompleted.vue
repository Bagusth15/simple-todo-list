<template>
  <button v-if="showClearCompletedButton" @click="clearCompleted">
    Clear Completed
  </button>
</template>

<script>
import { eventBus } from "@/eventBus.js";
export default {
  name: "todo-clear-completed",
  props: {
    showClearCompletedButton: {}
  },
  methods: {
    clearCompleted() {
      eventBus.$emit("clearCompletedTodos");
    }
  }
};
</script>
