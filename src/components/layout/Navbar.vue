


<template>
  <div>
    <div>
      <b-navbar toggleable="lg" type="dark" style="background-color:#303030">
        <div class="container">
          <b-navbar-brand href="#">
            <img src="../../assets/logo.png" width="100" height="45" alt>
          </b-navbar-brand>

          <b-navbar-toggle target="nav-collapse"></b-navbar-toggle>

          <b-collapse id="nav-collapse" is-nav>
            <b-navbar-nav>
              <b-nav-item-dropdown toggle-class="text-white" text="Link1" right>
                <b-dropdown-item href="#">Lorem ipsat!</b-dropdown-item>
                <b-dropdown-item href="#">Lbis impedit.</b-dropdown-item>
                <b-dropdown-item href="#">ipr dolore nam.</b-dropdown-item>
                <b-dropdown-item href="#">esse consequuntur</b-dropdown-item>
              </b-nav-item-dropdown>
              <b-nav-item href="#">
                <span class="color">Link2</span>
              </b-nav-item>
              <b-nav-item href="#">
                <span class="color">Link3</span>
              </b-nav-item>
              <b-nav-item href="#">
                <span class="color">Information Link</span>
              </b-nav-item>
            </b-navbar-nav>

            <b-navbar-nav class="ml-auto">
              <b-nav-item-dropdown toggle-class="text-white" text="User Link" right>
                <b-dropdown-item href="#">Lorem ipsat!</b-dropdown-item>
                <b-dropdown-item href="#">Lbis impedit.</b-dropdown-item>
                <b-dropdown-item href="#">ipr dolore nam.</b-dropdown-item>
                <b-dropdown-item href="#">esse consequuntur</b-dropdown-item>
              </b-nav-item-dropdown>

              <b-nav-item-dropdown right>
                <template v-slot:button-content>
                  <em class="color">About Us</em>
                </template>
                <b-dropdown-item href="#">Profile</b-dropdown-item>
                <b-dropdown-item href="#">Sign Out</b-dropdown-item>
              </b-nav-item-dropdown>
              <b-nav-item-dropdown right class="mr-5">
                <template v-slot:button-content>
                  <em style="color:orange">Sign In</em>
                </template>
                <b-dropdown-item href="#">Profile</b-dropdown-item>
                <b-dropdown-item href="#">Sign Out</b-dropdown-item>
              </b-nav-item-dropdown>
              <b-nav-item href="#">
                <i class="fas fa-shopping-cart"></i>
                <span class="ml-1 mr-1">0</span>
              </b-nav-item>
              <b-nav-item>
                <i class="fas fa-search"></i>
              </b-nav-item>
            </b-navbar-nav>
          </b-collapse>
        </div>
      </b-navbar>
    </div>
    <div>
      <header class="header2">
        <div class="container">
          <p style="padding:3px; margin:0px">
            Right
            <span style="font-weight:bold" class="mr-2">Now</span>
            <i class="fas fa-arrow-right"></i>
          </p>
        </div>
      </header>
    </div>
  </div>
</template>

<script>
export default {
  name: "Navbar"
};
</script>

<style scoped>
.color {
  color: white;
}
.header2 {
  background: #ff5000;
  color: #fff;
  text-align: left;
  overflow: auto;
}
</style>


