<template>
  <div>
    <TheHeader :title="pageHeader" />
    <TheFooter />
  </div>
</template>

<script setup>
import TheHeader from "./components/TheHeader.vue";
import TheFooter from "./components/TheFooter.vue";

const pageHeader = "Home Page Title";
</script>
