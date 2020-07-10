<template>
  <b-navbar toggleable="lg" type="light" variant="default">
    <b-navbar-brand :to="'/'">
      <img
        src="/img/vue-boilerplates.svg"
        class="d-inline-block align-top"
        alt="Vue Boilerplates"
        height="30px"
        width="auto"
      />
      Nexxtepp
    </b-navbar-brand>

    <b-navbar-toggle target="nav-collapse"></b-navbar-toggle>

    <b-collapse id="nav-collapse" is-nav>
      <b-navbar-nav> </b-navbar-nav>
      <b-navbar-nav class="ml-auto">
        <b-nav-item right :to="'/'">Home</b-nav-item>
        <b-nav-item right :to="'/company'">Company</b-nav-item>
        <b-nav-item right :to="'/about'">About</b-nav-item>
      </b-navbar-nav>
    </b-collapse>
  </b-navbar>
</template>
