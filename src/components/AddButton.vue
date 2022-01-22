<template v-slot:extension>
  <v-fab-transition>
    <v-btn v-show="!hidden" color="blue" fab dark small absolute top>
      <v-icon>mdi-plus</v-icon>
    </v-btn>
  </v-fab-transition>
</template>

<script>
export default {
  name: "AddButton",
};
</script>
