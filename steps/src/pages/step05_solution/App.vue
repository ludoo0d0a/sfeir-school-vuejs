<template>
  <section>
    <md-toolbar class="navBar">
      <a href="#/home">
        <img class="logo" src="/assets/images/logo-people.svg" />
      </a>
      <h2 class="md-title" style="flex: 1"></h2>
      <span class="link">
        <a href="#/people">Peoples</a>
      </span>
    </md-toolbar>
    <sfeir-home></sfeir-home>
  </section>
</template>

<script>
import Home from "./views/Home";

export default {
  components: {
    "sfeir-home": Home,
  },
};
</script>

<style scoped>
.navBar {
  background-color: #0168ab !important;
  background-image: url("/assets/images/bg_right.png");
  background-repeat: no-repeat;
  background-position: right;
  top: 0px;
  box-shadow: 0 2px 5px 0 rgba(0, 0, 0, 0.26);
  z-index: 1;
  color: white;
  margin-bottom: 10px;
  display: flex;
  align-items: center;
}

.logo {
  height: 56px;
}

.link {
  color: white;
}

a {
  color: inherit !important;
  text-decoration: none !important;
  height: 100%;
  margin: 0px 10px 0px 10px;
  border-bottom: 2px solid transparent;
  font-size: 1.3em;
  font-weight: normal;
  font-family: "Open Sans", sans-serif;
}

a:hover {
  border-bottom: 2px solid white !important;
}
</style>