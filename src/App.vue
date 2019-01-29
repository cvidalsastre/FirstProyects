<template>
  <v-app id="inspire">
    <prueba-template></prueba-template>
  </v-app>
</template>

<script>
import PruebaTemplate from "./components/PruebaTemplate";
export default {
  data: () => ({}),
  components: { "prueba-template": PruebaTemplate },
  props: {}
};
</script>
