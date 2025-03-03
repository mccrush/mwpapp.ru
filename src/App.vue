<script setup>
import BlockCover from "./components/BlockCover.vue";
import BlockScreen from "./components/BlockScreen.vue";
import BlockVideo from "./components/BlockVideo.vue";
</script>

<template>
  <BlockCover />
  <BlockScreen />
  <BlockVideo />

  <!-- <div
    class="cover-container d-flex w-100 vh-100 p-3 mx-auto flex-column justify-content-center"
  >
    <HelloWorld />
    <HelloWorld />
  </div> -->
</template>

<style>
.my-dvw-100 {
  width: 100dvw;
}
.my-dvh-100 {
  height: 100dvh;
}
</style>
