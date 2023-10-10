<template>
  <Layout>
    <AdminPage></AdminPage>

    <!-- Default content for /admin when there's no nested route -->
    This is the admin page.
    <br />
    <g-link to="/admin/textseiten">Go to Textseiten</g-link>
    <br />
    <g-link :to="'/admin/textseiten/' + page.id">Go to Textseiten by id</g-link>
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
