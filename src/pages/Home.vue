<template>
  <b-container fluid class="text-center p-0 m-0">
    <Navbar />
    <b-jumbotron
      header="Vue Boilerplates"
      lead="vue-bootstrapvue-boilerplate"
      header-tag="h2"
      fluid
      class="m-0 p-0 p-3"
      header-level="4"
    >
      <b-row align-h="center" no-gutters class="mb-4">
        <img width="130px" height="auto" src="/img/vue-boilerplates.svg" />
      </b-row>
      <p class="m-0 p-0">
        Vue + BootstrapVue + Lazy loading and code splitting
      </p>
    </b-jumbotron>
    <b-container>
      <b-row>
        <b-col>
          <b-jumbotron
            header="Why Vue Boilerplates?"
            bg-variant="white"
            text-variant="dark"
            border-variant="white"
            header-tag="h2"
            class="text-left m-0"
            header-level="5"
          >
            <p>
              While mobile-first approach becomes a standard and uncertain
              network conditions are something we should always take into
              consideration, it’s harder and harder to keep your application
              loading fast. Vue Boilerplates was built with vue.js performance
              optimization techniques that make them loading instantly and
              perform smooth 🚀.
            </p>
          </b-jumbotron>
        </b-col>
        <b-col>
          <b-jumbotron
            header="Lets grow together!"
            lead="Please consider becoming a donor 🙏."
            bg-variant="white"
            text-variant="dark"
            border-variant="white"
            header-tag="h2"
            class="text-left m-0"
            header-level="5"
          >
            <p>
              Make a custom one time or recurring contribution to support my
              open source projects
            </p>
            <b-button
              variant="success"
              target="_blank"
              href="https://opencollective.com/vue-boilerplates"
              >Donate</b-button
            >
          </b-jumbotron>
        </b-col>
      </b-row>
    </b-container>
  </b-container>
</template>

<script>
import Navbar from "@/components/Navbar.vue";

export default {
  name: "Home",
  components: {
    Navbar,
  },
};
</script>

<style scoped>
.block {
  margin: 3rem 2rem 3rem 2rem;
}
h1,
h2 {
  margin: 0;
}
h3 {
  margin-top: 0.5rem;
}
img {
  margin-bottom: 1rem;
}
.donate-btn {
  display: inline-block;
  font-weight: 400;
  text-align: center;
  vertical-align: middle;
  color: #fff;
  background-color: #1e7e34;
  border-color: #1c7430;
  cursor: pointer;
  user-select: none;
  border: 1px solid transparent;
  padding: 0.375rem 0.75rem;
  font-size: 1rem;
  line-height: 1.5;
  border-radius: 0.25rem;
  text-decoration: none;
}
.donate-btn:hover {
  color: #fff;
  background-color: #218838;
  border-color: #1e7e34;
}
</style>
