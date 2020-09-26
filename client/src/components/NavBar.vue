<template>
  <div>
    <nav class="navbar is-spaced is-light" role="navigation" aria-label="main navigation">
      <div class="navbar-brand">
        <router-link class="navbar-item" to="/">
          <img
            src="https://insmac.org/uploads/posts/2019-04/1555139219_intl_interior_appicon.png"
            alt="Bulma: Free, open source, and modern CSS framework based on Flexbox"
            width="32"
            height="64"
          />
        </router-link>

      </div>
      <div class="navbar-menu">
        <div class="navbar-start">
          <h1 class="container is-fluid">Landing Page</h1>
        </div>
        <div class="navbar-end">
          <router-link class="navbar-item" to="home"> About Me </router-link>
          <router-link class="navbar-item" to="home"> My Works </router-link>
          <router-link class="navbar-item" to="home"> Contact Me </router-link>
        </div>
      </div>
    </nav>
  </div>
</template>

<script>
export default {
  name: "NavBar",
};
</script>

<style lang="scss" scoped>
</style>