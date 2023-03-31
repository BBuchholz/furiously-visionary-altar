<template>
  <div class="home">
    <img alt="STS logo" src="../assets/STS_Shepton-logo.png" />
    <HelloWorld msg="Shepton Transmission Services" />
  </div>
</template>

<script lang="ts">
import { defineComponent } from "vue";
import HelloWorld from "@/components/HelloWorld.vue"; // @ is an alias to /src

export default defineComponent({
  name: "HomeView",
  components: {
    HelloWorld,
  },
});
</script>

<style>
img {
  max-width: 100%;
  height: auto;
}
</style>
