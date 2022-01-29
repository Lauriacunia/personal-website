<template>
  <v-container>
    <v-row class="text-center">
      <h1 class="principal">Hello World</h1>
    </v-row>
    <v-row class="text-center">
      <p class="text">This is a simple with Source Code Pro Font.</p>
    </v-row>
    <v-divider></v-divider>
  </v-container>
</template>

<script>
export default {
  name: "HelloWorld",

  data: () => ({}),
};
</script>

<style scoped>
@import url("https://fonts.googleapis.com/css2?family=Abril+Fatface&display=swap");
@import url("https://fonts.googleapis.com/css2?family=Source+Code+Pro&display=swap");

.principal {
  font-family: "Abril Fatface", cursive !important;
  font-size: 150px !important;
}
.text {
  font-family: "Source Code Pro", monospace !important;
}
</style>
