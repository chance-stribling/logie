<template>
  <v-app-bar color="black" scroll-behavior="elevate">
    <v-row>
      <v-col class="text-center">
        <v-btn @click="$router.push('/')">Home</v-btn>
        <v-btn @click="$router.push('/work')">Work</v-btn>
        <v-btn @click="$router.push('/skills')">Skills</v-btn>
      </v-col>
      <v-col class="text-center">
        <v-app-bar-title @click="$router.push('/')">Logan Gibson</v-app-bar-title>
      </v-col>
      <v-col class="text-center">
        <v-btn @click="$router.push('/about')">About</v-btn>
        <v-btn @click="$router.push('/contact')">Contact</v-btn>
      </v-col>
    </v-row>
  </v-app-bar>
</template>
<style scoped></style>
<script>
export default {}
</script>
