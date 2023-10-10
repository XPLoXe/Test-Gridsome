<template>
  <div>
    <h1>{{ message }}</h1>
    <button @click="incrementCounter">Click me</button>
    <p>Counter: {{ counter }}</p>
  </div>
</template>

<script>
export default {
  data() {
    return {
      message: "Hello, world!",
      counter: 0,
    };
  },
  methods: {
    incrementCounter() {
      this.counter++;
    },
  },
};
</script>

<style>
/* Add your styles here */
</style>
