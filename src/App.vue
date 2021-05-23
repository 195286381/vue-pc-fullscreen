<template>
  <div class="app-wrapper">
    <div class="app">
      <router-view />
    </div>
  </div>
</template>

<style>
  * {
    margin: 0;
    padding: 0;
  }
  html, body {
    overflow: hidden;

  }
  .app-wrapper {
    /*overflow: hidden;*/
    width: 100vw;
    height: 100vh;
    background: url('./assets/1.jpeg') no-repeat center / cover;
  }

  .app {
    width: 1920px;
    height: 1080px;
  }
</style>
