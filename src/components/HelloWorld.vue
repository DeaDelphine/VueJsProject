<script setup>
defineProps({
  msg: {
    type: String,
    required: true
  }
})
const classTitle = "greetings"
</script>

<template>

<div :class="classTitle">
    <h1>{{ msg }}</h1>
  </div>
</template>

