<template>
  <v-app>
    <v-app-bar app color="danger" dark>
      <v-toolbar-title>Monst Used Words</v-toolbar-title>
    </v-app-bar>

    <v-main> 
      <Home />
    </v-main>
  </v-app>
</template>

<script>
import Home from "./components/Home";

export default {
  name: "App",

  components: {
    Home
  },

  data: () => ({
    //
  })
};
</script>
