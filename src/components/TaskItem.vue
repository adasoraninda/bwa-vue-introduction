<template>
  <div>
    <input type="checkbox" class="form-check-input" v-bind:id="task.id" />
    <label
      v-bind:class="{ 'item-completed': task.isDone }"
      class="form-check-label"
      v-bind:for="task.id"
      >{{ task.name }}</label
    >
  </div>
</template>

<script>
export default {
  name: "TaskItem",
  props: ["task"],
};
</script>