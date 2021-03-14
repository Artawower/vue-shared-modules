<template>
  <HelloWorld msg="Our shared component" />
</template>

<script lang="ts">
import { Options, Vue } from "vue-class-component";
import { HelloWorld } from "shared";

 import 'shared/dist/shared.css';

@Options({
  components: {
    HelloWorld
  }
})
export default class App extends Vue {}
</script>

