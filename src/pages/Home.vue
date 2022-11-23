<template>
  <h1>Home</h1>
</template>

<script setup>
import { defineAsyncComponent } from "vue";

function load(file) {
  return defineAsyncComponent(() => import(`../components/${file}.vue`));
}
</script>

 
