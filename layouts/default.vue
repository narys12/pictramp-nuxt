<template>
  <v-app light toolbar footer>
    <v-toolbar class="white" light dense>
      <v-toolbar-title>PicTramp</v-toolbar-title>
      <v-text-field class="ml-4" prepend-icon="search" hide-details single-line></v-text-field>
      <v-btn icon>
        <v-icon>more_vert</v-icon>
      </v-btn>
      <v-btn icon>
        <v-icon>mail</v-icon>
      </v-btn>
      <v-btn icon>
        <v-icon>event_busy</v-icon>
      </v-btn>
      <v-btn icon>
        <v-icon>account_circle</v-icon>
      </v-btn>
    </v-toolbar>
  </v-app>
</template>

<script>
  export default {
    data() {
      return {}
    }
  }
</script>