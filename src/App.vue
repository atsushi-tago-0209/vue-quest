<template>
  <v-app>
    <v-toolbar
      dark
      src="https://cdn.vuetifyjs.com/images/backgrounds/vbanner.jpg"
      max-height="60"
    >
    <v-toolbar-title>YouTube Curation</v-toolbar-title>
    </v-toolbar>
    <v-main>
      <HelloWorld/>
    </v-main>
    <v-toolbar
      dark
      src="https://cdn.vuetifyjs.com/images/backgrounds/vbanner.jpg"
      max-height="60"
    >
    <v-spacer></v-spacer>
      <p>@QuestAcademia</p>
    </v-toolbar>
  </v-app>
</template>

<script>
import HelloWorld from './components/HelloWorld';

export default {
  name: 'App',

  components: {
    HelloWorld,
  },

  data: () => ({
    //
  }),
};
</script>
