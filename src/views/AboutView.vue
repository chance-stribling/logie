<template>
  <div id="about" class="px-15 py-5" style="min-height: 600px; background-color: white">
    <v-row>
      <v-col class="d-flex flex-column" style="max-width: 50vw">
        <h1 class="mb-10 font-weight-bold">About Me</h1>
        <p class="mb-5">Hi, I'm Logan!</p>
        <p class="mb-5">
          At 19, I'm on a journey of self-discovery, navigating life's twists and turns with a heart
          rooted in Louisiana and aspirations reaching for the sky in Tennessee. I'm captivated by
          the melodies of life, seeking harmony between the familiarity of my roots and the
          uncharted territories of my dreams. Originally from Louisiana, the bayou's warmth still
          flows in my veins, carrying the rich tapestry of Cajun culture and the spirited essence of
          Southern hospitality. But now, I find myself in the rolling hills of Tennessee, drawn by
          its vibrant energy and the promise of new beginnings.
        </p>
        <p>
          Currently, I'm on the brink of a thrilling chapter—college. As I weave through
          applications and ponder the infinite possibilities ahead, I'm eager to immerse myself in
          knowledge, fueled by an insatiable curiosity for learning and a passion for understanding
          the world. Yet, beyond academics, I'm on a quest for spiritual alignment. In the quiet
          moments, I seek solace in nature's embrace, finding meaning in the whispers of the wind
          and the rustle of leaves. Exploring spirituality, I'm discovering the depths of my soul,
          piecing together the mosaic of beliefs that resonate with my essence. Life's a canvas, and
          I'm embracing each stroke with open arms, painting my story with experiences that shape my
          identity and fuel my aspirations.
        </p>
        <v-col class="d-flex flex-column align-center mt-5">
          <v-btn href="/files/stare.jpg" color="black" download>Download My Resume</v-btn>
        </v-col>
        <v-col class="d-flex flex-row justify-space-evenly">
          <v-icon size="x-large" icon="mdi-instagram"></v-icon>
          <v-icon size="x-large" icon="mdi-twitter"></v-icon>
          <v-icon size="x-large" icon="mdi-linkedin"></v-icon>
        </v-col>
      </v-col>
      <v-col class="d-flex justify-center align-center">
        <img src="../assets/images/redhead.jpg" style="width: auto; height: 450px" alt="" />
      </v-col>
    </v-row>
  </div>
</template>
