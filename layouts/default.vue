<template>
  <v-app dark>
    <es-header />
    <Nuxt />
  </v-app>
</template>

<script>
import EsHeader from "@/components/EsHeader";
export default {
  name: "DefaultLayout",
  components: {
    EsHeader,
  },
  data() {
    return {};
  },
};
</script>
