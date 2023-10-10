<template>
  <AdminPage>
    <Layout>
      <!-- Default content for /admin when there's no nested route -->
      This is the admin page.
      <g-link to="/admin/textseiten">Go to Textseiten</g-link>
      <br />
      <g-link :to="'/admin/textseiten/' + page.id"
        >Go to Textseiten by id</g-link
      >
    </Layout>
  </AdminPage>
</template>

<script>
import AdminPage from "../components/AdminPage.vue";

//initialize vue2 data
export default {
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
