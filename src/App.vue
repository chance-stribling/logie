<script setup>
import { RouterView } from 'vue-router'
import TopBar from './components/TopBar.vue';
</script>

<template>
  <v-app id="app">
    <TopBar/>
    <v-main>
      <v-container fluid class="pa-0">
        <RouterView />
      </v-container>
    </v-main>
  </v-app>
</template>

<style scoped></style>
