<template>
  <v-row>
    <v-col @keydown>
      <v-text-field label="Search" :value="tic" @input="search = $event.terget.value"></v-text-field>
    </v-col>
  </v-row>
</template>

<script>
export default {
  name: "Search",
  data() {
    return {
      search: ""
    };
  }
};
</script>
