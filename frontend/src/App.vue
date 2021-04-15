<template>
  <div>
    <nav class="nav-wrapper">
      <a href="/" class="brand-logo center">Web App Manifest Generator</a>
    </nav>
    <Form></Form>
  </div>
</template>

<script>
import Form from "./components/Form.vue";

export default {
  name: "App",
  components: {
    Form,
  },
};
</script>

<style scoped>
@import "./styles/app.css";
@import "./styles/responsive.css";
</style>
