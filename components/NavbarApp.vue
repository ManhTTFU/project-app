<template>
  <div class="navbar-app">
    <b-container>
      <b-row>
        <b-col>
          <b-navbar
            toggleable="md"
            variant="sencondary">
             <b-navbar-toggle target="nav_collapse"></b-navbar-toggle>
             <b-navbar-brand
              href="#"
              class="navbar-title">AppStore</b-navbar-brand>
             <b-collapse
              is-nav
              id="nav_collapse">
              <b-navbar-nav class="navbar-icon">
                <b-nav-item href="#">Ios</b-nav-item>
                <b-nav-item href="#">Android</b-nav-item>
                <b-nav-item href="#">Support</b-nav-item>
                <b-nav-item href="#">Consult</b-nav-item>
              </b-navbar-nav>
              <b-navbar-nav class="ml-auto">
                <b-button size="sm">Login</b-button>
              </b-navbar-nav>
             </b-collapse>
          </b-navbar>
        </b-col>
      </b-row>
    </b-container>
  </div>
</template>
<style>
.navbar-app {
  position: fixed;
  background-color: white;
  z-index: 1;
  width: 100%;
}
.navbar-title {
  font-weight: bold;
  font-size: 30px;
}
.navbar-icon {
  margin-left: 590px;
  font-size: 16px;
}
</style>
