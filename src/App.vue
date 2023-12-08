<script setup>
import { RouterView } from 'vue-router'
import TopBar from './components/TopBar.vue'
import Footer from './components/Footer.vue'
</script>

<template>
  <v-app id="app">
    <TopBar />
    <v-main>
      <v-container fluid class="pa-0">
        <RouterView />
        <Footer />
      </v-container>
    </v-main>
  </v-app>
</template>

<style scoped></style>
