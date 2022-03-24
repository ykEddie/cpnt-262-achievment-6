<template>
  <header>
    <h1>{{ props.title }}</h1>
    <p>Using props to pass information</p>
  </header>
</template>

<script setup>
import { defineProps } from "vue";
const props = defineProps({
  title: {
    type: String,
    default: "Default Text",
  },
});
</script>

<style>
header {
  background-color: gold;
  margin-top: auto;
}
</style>