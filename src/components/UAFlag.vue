<template>
  <div class="min-h-[10rem] blur-3xl bg-blue-500 blue"></div>
  <div class="min-h-[10rem] blur-3xl bg-yellow-300 yellow"></div>
</template>

<style scoped>
.yellow {
  position: absolute;
  /* top: 200px; */
  /* left: 100px; */
  height: 20vh;
  width: 60vw;

  animation: yellow 8s infinite ease;
}

.blue {
  position: absolute;
  /* top: 0px; */
  /* right: 0vh; */
  height: 20vh;
  width: 60vw;

  animation: blue 8s infinite ease;
}

.red {
  background-color: var(--red);
  position: absolute;
  right: 0;
  /* top: 300px; */
  height: 16vh;
  width: 16vw;

  animation: red 8s infinite linear;
}

@keyframes blue {
  0% {
    top: 200px;
    left: 100px;
    transform: scale(1);
  }
  30% {
    top: 300px;
    left: 150px;
    transform: scale(1.2);
  }
  60% {
    top: 100px;
    left: 200px;
    transform: scale(1.3);
  }
  100% {
    top: 200px;
    left: 100px;
    transform: scale(1);
  }
}

@keyframes yellow {
  0% {
    top: 80px;
    right: -20px;
    transform: scale(1.2);
  }
  30% {
    top: 300px;
    right: -20px;
    transform: scale(1);
  }
  60% {
    top: 200px;
    right: 100px;
    transform: scale(1);
  }
  100% {
    top: 80px;
    right: -20px;
    transform: scale(1.2);
  }
}

@keyframes red {
  0% {
    top: 250px;
    right: 0px;
    transform: scale(1);
  }
  30% {
    top: 150px;
    right: 150px;
    transform: scale(1.4);
  }
  60% {
    top: 250px;
    right: 100px;
    transform: scale(1);
  }
  100% {
    top: 250px;
    right: 0px;
    transform: scale(1);
  }
}
</style>
