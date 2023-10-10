<template>
  <Layout>
    <slot></slot>
    <g-link to="/admin">Go to Admin Index</g-link>
    <br />
    <g-link to="/admin/text">Go to Text</g-link>
    <br />
    <g-link to="/approach">Go to Approach</g-link>
  </Layout>
</template>

<script>
export default {
  data() {
    return {};
  },
};
</script>
