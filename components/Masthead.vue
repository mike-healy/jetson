<template>
  <div class="appear-me">
    <img
    src="/at-pool_600.jpg"
    alt="Jetson chillin at the pool"
    srcset="/at-pool_600.jpg 600w, /at-pool_1300.jpg 1300w"
    sizes="width: 400px"
    class="circle">
  </div>
</template>

<style>
.appear-me {
  animation: 1s appear;
  margin: auto;
  max-width: 400px;
}

@keyframes appear {
  0% {
    opacity: 0;
  }
}

img.circle {
  clip-path: circle();
}
</style>
