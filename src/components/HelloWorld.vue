<script setup>
import { ref } from "vue";

defineProps({
  msg: String,
});

const count = ref(0);
</script>

<template>
  <div class="text-center mt-5 pt-5">
    <h1 class="display-4"><strong>MWP</strong><br />менеджер веб-проектов</h1>

    <p class="fs-4 mt-5">
      Вы можете
      <a href="https://app.mwpapp.ru" target="_blank">перейти в приложение</a
      ><br />
      или сначала
      <a href="https://doc.mwpapp.ru" target="_blank">ознакомиться</a> с
      руководством пользователя
    </p>
  </div>
</template>

<style scoped>
</style>
