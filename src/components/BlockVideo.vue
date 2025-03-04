<template>
  <div
    class="my-vh-50 d-flex d-md-none flex-column justify-content-center align-items-center bg-dark"
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
  <div
    class="d-none d-md-flex flex-column justify-content-center align-items-center bg-dark vh-100"
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
  height: calc(100% / 1.7);
}

.my-vh-50 {
  height: 50dvh;
}
</style>