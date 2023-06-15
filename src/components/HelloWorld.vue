<template>
  <main>
    <h1>API Style !</h1>
    <p>{{ message }}</p>
    <button @click="hello(`Mathis`)">Change Message</button>
    <test />
  </main>
</template>

<script>
export default {
  name: "App",
  data: () => ({
    message: "Hello World",
  }),
  methods: {
    hello(name) {
      this.message = `Hello World ${name}`;
    },
  },
};
</script>

<style>
* {
  margin: 0;
  padding: 0;
}
main {
  height: 80vh;
  width: 100vw;
  display: flex;
  justify-content: center;
  align-items: center;
  flex-direction: column;
  background-color: antiquewhite;
}
</style>
