<template>
  <div>
    <v-app-bar>
      <v-icon large>account_circle</v-icon>
      <v-spacer></v-spacer>
      <Search />
    </v-app-bar>
    <main class="grid"></main>
  </div>
</template>

<script>
import Search from "./components/Saerch";
export default {
  name: "App",
  components: {
    Search
  },
  data: () => ({
    //
  })
};
</script>
