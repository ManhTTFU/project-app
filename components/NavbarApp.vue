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
                <b-nav-form>
                  <b-form-input
                  size="sm"
                  class="mr-sm-2"
                  type="text"
                  placeholder="Search"/>
                  <b-button
                  size="sm"
                  class="my-2 my-sm-0"
                  type="submit">Search</b-button>
                </b-nav-form>
                <b-nav-item-dropdown right>
                  <template slot="button-content">
                    <em>User</em>
                  </template>
                  <b-dropdown-item href="#">Profile</b-dropdown-item>
                  <b-dropdown-item href="#">Signout</b-dropdown-item>
                </b-nav-item-dropdown>
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
  margin-left: 359px;
  font-size: 16px;
}
</style>
