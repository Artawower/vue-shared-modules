<template>
  <h1 class="awesome-title">{{ msg }}</h1>
</template>

<script lang="ts">
import { defineComponent } from "vue";

export default defineComponent({
  props: {
    msg: String
  }
});
</script>

<style scoped lang="scss">
.awesome-title {
  color: purple;
}
</style>
