<template>
  <div
    class="d-flex flex-column justify-content-center align-items-center bg-dark vh-100"
  >
    <iframe
      class="my-video"
      src="https://rutube.ru/play/embed/270a800480c4071b9543f01ef123f045/"
      frameBorder="0"
      allow="clipboard-write; autoplay"
      webkitAllowFullScreen
      mozallowfullscreen
      allowFullScreen
    ></iframe>
  </div>
</template>

<style scoped>
.my-video {
  width: 100%;
  max-width: 990px;
  height: calc(100% / 1.8);
}

/* 
width="720"
      height="405"

*/
</style>