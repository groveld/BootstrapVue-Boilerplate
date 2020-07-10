<template>
  <b-container fluid class="text-center p-0 m-0">
    <Navbar />
    <b-jumbotron
      header="Company Info"
      lead=""
      header-tag="h2"
      fluid
      class="m-0"
      header-level="4"
    >
    </b-jumbotron>
    <b-table striped hover :items="items" :fields="fields"></b-table>
  </b-container>
</template>

<script>
import Navbar from "@/components/Navbar.vue";

export default {
  name: "Company",
  components: {
    Navbar,
  },
  data() {
    return {
      fields: ["first_name", "last_name", "age"],
      items: [
        {
          isActive: true,
          age: 40,
          first_name: "Dickerson",
          last_name: "Macdonald",
        },
        { isActive: false, age: 21, first_name: "Larsen", last_name: "Shaw" },
        { isActive: false, age: 89, first_name: "Geneva", last_name: "Wilson" },
        { isActive: true, age: 38, first_name: "Jami", last_name: "Carney" },
      ],
    };
  },
};
</script>
