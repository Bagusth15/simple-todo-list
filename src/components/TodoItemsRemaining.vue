<template>
  <div>{{ remaining }} items left</div>
</template>

<script>
export default {
  name: "todo-remainings",
  computed: {
    remaining() {
      return this.$store.getters.remaining;
    }
  }
};
</script>
