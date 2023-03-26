<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <p>
      Shubtown Transmission Services is a full-service transmission shop located
      in Shubtown, Wisconsin. We offer a wide range of services, including
      transmission repairs, rebuilds, and replacements. We also offer a variety
      of other services, such as oil changes, tune-ups, and brake repairs.
    </p>
    <p>
      We are a family-owned and operated business, and we have been serving the
      Shubtown community for over 20 years. We are committed to providing our
      customers with the highest quality of service and the best possible value.
    </p>
    <p>
      Contact us today to schedule an appointment or to learn more about our
      services.
    </p>
    <p>
      For a guide and recipes on how to configure / customize this project,<br />
      check out the
      <a href="https://cli.vuejs.org" target="_blank" rel="noopener"
        >vue-cli documentation</a
      >.
    </p>
  </div>
</template>

<script lang="ts">
import { defineComponent } from "vue";

export default defineComponent({
  name: "HelloWorld",
  props: {
    msg: String,
  },
});
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
