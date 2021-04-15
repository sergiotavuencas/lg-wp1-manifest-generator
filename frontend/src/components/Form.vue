<template>
  <div class="row">
    <form id="form" class="col m6 s12 row">
      <p class="desc col s12">
        The
        <a href="https://www.w3.org/TR/appmanifest/" target="_blank"
          >Web App Manifest</a
        >
        is a JSON document that provides application metadata for
        <a
          href="https://developers.google.com/web/progressive-web-apps?hl=en"
          target="_blank"
          >Progressive Web Apps</a
        >. Use the form below to generate the JSON file and optionally upload an
        app icon.
      </p>

      <div class="input-field col s12 l6">
        <label for="name" autofocus class="active">
          App Name
        </label>
        <input
          placeholder="Placeholder"
          id="name"
          type="text"
          class="validate"
        />
      </div>
    </form>
  </div>
</template>

<script>
export default {
  name: "Form",
  props: {},
};
</script>

<style scoped>
@import "../styles/form.css";
</style>
