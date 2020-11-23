<template>
  <div style="box-shadow: 3px 3px 3px 3px White">
    <div>
      <b-navbar toggleable="lg" type="light" variant="light">
        <b-navbar-brand href="#">
          <img
            src="https://freesvg.org/img/chef-restaurant-logo-publicdomainvectors.png"
            width="40px"
            height="40px"
          />
          Restoran Astoria
        </b-navbar-brand>

        <b-navbar-toggle target="nav-collapse"></b-navbar-toggle>

        <b-collapse id="nav-collapse" is-nav>
          <b-navbar-nav>
            <b-nav-item href="#">Rezerviraj stol</b-nav-item>
            <b-nav-item href="#">Naruči unaprijed</b-nav-item>
            <b-nav-item href="#galerija">Galerija</b-nav-item>
          </b-navbar-nav>
        </b-collapse>
      </b-navbar>
    </div>
  </div>
</template>

<script>
export default {
  name: "Navbar",
};
</script>