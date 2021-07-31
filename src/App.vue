<template>
  <div>Hello {{ name }}!</div>
</template>

<script lang="ts">
import { defineComponent } from "vue";

export default defineComponent({
  data: () => ({
    name: "Vue"
  })
});
</script>
