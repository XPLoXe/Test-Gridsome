<template>
  <div>
    <h1>{{ message }}</h1>
    <slot></slot>
  </div>
</template>

<script>
export default {
  data() {
    return {
      message: "Admin Page",
    };
  },
};
</script>

<style>
/* Add your styles here */
</style>
