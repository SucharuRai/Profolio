<template>
  <div>
    <b-navbar toggleable="lg" type="dark" variant="info">
      <b-navbar-brand href="#">Profile Portfolio</b-navbar-brand>

      <b-navbar-toggle target="nav-collapse"></b-navbar-toggle>
      <b-collapse id="nav-collapse" is-nav>
        <!-- Right aligned nav items -->
        <b-navbar-nav class="ml-auto">
          <b-navbar-nav>
            <b-nav-item href="#">ABOUT.ME</b-nav-item>
          </b-navbar-nav>
          <b-navbar-nav>
            <b-nav-item href="#">
              <img src="~/static/k_hindi.png" alt height="auto" width="25px" />
              कVITA
            </b-nav-item>
          </b-navbar-nav>
          <!-- <b-nav-item-dropdown text="Lang" right>
          <b-dropdown-item href="#">EN</b-dropdown-item>
          <b-dropdown-item href="#">ES</b-dropdown-item>
          <b-dropdown-item href="#">RU</b-dropdown-item>
          <b-dropdown-item href="#">FA</b-dropdown-item>
          </b-nav-item-dropdown>-->
          <b-navbar-nav>
            <b-nav-item href="#">CONNECT</b-nav-item>
          </b-navbar-nav>
        </b-navbar-nav>
      </b-collapse>
    </b-navbar>
  </div>
</template>

<style scoped>
.navbar {
  position: fixed;
  width: 100vw;
  z-index: 9999;
}

.bg-info {
  /* background: linear-gradient( 171.8deg,  rgba(5,111,146,1) 13.5%, rgba(6,57,84,1) 78.6% ); */
  background: rgb(17, 8, 117);
  background: radial-gradient(
    circle,
    rgba(17, 8, 117, 1) 35%,
    rgba(12, 12, 167, 1) 79%,
    rgba(12, 39, 199, 1) 100%
  );
  font-size: 1.2rem;
}
</style>