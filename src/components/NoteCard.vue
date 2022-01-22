<template>
  <v-card class="mx-auto" max-width="344" outlined>
    <v-list-item three-line>
      <v-list-item-content>
        <v-list-item-title class="text-h5 mb-1">Note</v-list-item-title>
        <v-list-item-subtitle
          >Greyhound divisely hello coldly fonwderfully</v-list-item-subtitle
        >
      </v-list-item-content>
    </v-list-item>

    <p class="hashtag">#hashtag</p>

    <v-card-actions>
      <v-btn outlined text>Edit</v-btn>
      <v-btn outlined text>Delete</v-btn>
    </v-card-actions>
  </v-card>
</template>

<script>
export default {
  name: "NoteCard",
};
</script>
