<template>
  <HolaMundo />
</template>

<script lang="ts">
import { defineComponent } from "vue";
import HolaMundo from "./components/HolaMundo.vue";

export default defineComponent({
  name: "App",
  components: { 
    HolaMundo
  },
});
</script>

<style></style> 
