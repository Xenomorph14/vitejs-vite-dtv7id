<script setup>
import { ref } from 'vue';
import {} from 'video.js';
defineProps({
  msg: String,
});

const count = ref(0);
</script>

<template>
  <link
    href="https://unpkg.com/video.js@7/dist/video-js.min.css"
    rel="stylesheet"
  />

  <!-- City -->
  <link
    href="https://unpkg.com/@videojs/themes@1/dist/city/index.css"
    rel="stylesheet"
  />

  <!-- Then, in the player -->
  <video class="video-js vjs-theme-city" ...></video>
</template>

<style scoped>
.read-the-docs {
  color: #888;
}
</style>
