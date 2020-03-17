<template>
  <div>{{ remaining }} items left</div>
</template>

<script>
export default {
  name: "todo-remainings",
  props: {
    remaining: {
      type: Number,
      required: true
    }
  }
};
</script>
