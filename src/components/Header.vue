<template>
  <header>
    <h1>Voici le Header</h1>
  </header>
</template>

<script>
export default {
  props: {
    title: String,
    message: String,
  },
};
</script>

<style>
header {
  height: 10vh;
  display: flex;
  justify-content: center;
  align-items: center;
  background-color: yellow;
}

header > h1 {
  background-color: red;
  min-width: 300px;
  text-align: center;
}
</style>
