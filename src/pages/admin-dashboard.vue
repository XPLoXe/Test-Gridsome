<template>
  <Layout>
    This is the admin page.
    <g-link to="/admin/text/">Go to Text</g-link>
  </Layout>
</template>

<script>
import AdminPage from "../components/AdminPage.vue";

//initialize vue2 data
export default {
  name: "admin-dashboard",
  components: {
    AdminPage,
  },
  data() {
    return {
      page: {
        id: "textseiten",
      },
    };
  },
};
</script>
