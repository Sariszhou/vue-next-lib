<template>
  <div class="app-container">app</div>
  <span class="text">text</span>
</template>

<script lang="ts">
import { defineComponent } from "vue";
import HelloWorld from "./components/HelloWorld.vue";

export default defineComponent({
  name: "App",
  components: {
    HelloWorld,
  },
});
</script>

<style lang="scss">
.text {
  color: $primary-color;
}
</style>
