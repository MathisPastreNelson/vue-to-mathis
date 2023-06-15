<template>
  <footer>
    <h2>Footer position</h2>
  </footer>
</template>

<script>
export default {
  name: "App",
};
</script>

<style>
footer {
  display: flex;
  justify-content: center;
  align-items: center;
  height: 10vh;
  background-color: yellow;
}

footer > h2 {
  background-color: red;
  min-width: 300px;
  text-align: center;
}
</style>
