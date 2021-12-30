<template>
  <div :key="task.id" v-for="tasks in Tasks">
    <h3>{{ tesk.text }}</h3>
  </div>
</template>

<script>
export default {
  name: 'Tasks',
  props: {
    tasks: Array
  }
}
</script>