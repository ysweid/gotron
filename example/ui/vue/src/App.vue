<template>
  <h1 className="topic">Hello Gotron / VueJS</h1>
</template>

<script>
export default {
  name: 'App'
}
</script>

<style>
  /* @font-face {
      font-family: 'Roboto';
      src: url(./Roboto-Light.ttf) format("truetype");
  } */

  body {
    height: 100%;
    width: 100%;
    display: flex;
    position: fixed;
    align-items: center;
    justify-content: center;
    font-family: Roboto;
    background: #ba42ff;
  }

  .topic {
    color: #3a2c38;
  }
</style>