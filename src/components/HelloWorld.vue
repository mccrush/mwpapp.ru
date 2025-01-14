<script setup>
import { ref } from "vue";

defineProps({
  msg: String,
});

const count = ref(0);
</script>

<template>
  <div class="pb-5">
    <h1 class="display-1 fw-normal lh-1 m-0"><strong>MWP</strong></h1>
    <p class="display-6 lh-1 m-0">менеджер веб-проектов</p>

    <div class="row mt-5">
      <div class="col-12 col-sm-6">
        <a
          class="btn btn-outline-light w-100"
          href="https://app.mwpapp.ru"
          target="_blank"
          >Приложение</a
        >
      </div>
      <div class="col-12 col-sm-6 mt-3 mt-sm-0">
        <a
          class="btn btn-outline-light w-100"
          href="https://doc.mwpapp.ru"
          target="_blank"
          >Руководство</a
        >
      </div>
    </div>
  </div>
</template>

<style scoped>
.display-1 {
  font-size: calc(5.625rem + 4.5vw);
}
</style>
