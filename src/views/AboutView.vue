<template>
  <div class="about">
    <h1>This is an about page</h1>
    <AboutLinks />
  </div>
</template>

<script lang="ts">
import { defineComponent } from "vue";
import AboutLinks from "@/components/AboutLinks.vue"; // @ is an alias to /src

export default defineComponent({
  name: "AboutView",
  components: {
    AboutLinks,
  },
});
</script>
