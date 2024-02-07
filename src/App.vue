<script setup>
import { RouterView } from 'vue-router'
</script>

<template>
  ewq
  <v-app>
    <v-app-bar :elevation="25">
      <template v-slot:prepend>
        <v-app-bar-nav-icon></v-app-bar-nav-icon>
      </template>

      <v-app-bar-title>Application Bar</v-app-bar-title>

      <template v-slot:append>
        <v-btn icon="mdi-heart"></v-btn>

        <v-btn icon="mdi-magnify"></v-btn>

        <v-btn icon="mdi-dots-vertical"></v-btn>
      </template>
    </v-app-bar>
  </v-app>
  ewq
  <RouterView />
</template>

<style scoped></style>
