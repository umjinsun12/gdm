<template lang="html">
  <b-navbar class="fixed-top" toggleable="md" type="dark" variant="info">
    <b-navbar-toggle target="nav_collapse"></b-navbar-toggle>
    <div class="text-center navbar-brand-wrapper d-flex align-items-top justify-content-center">
      <a class="navbar-brand brand-logo" href="/"><img src="../../assets/images/logo.png" alt="logo"/></a>
      <a class="navbar-brand brand-logo-mini" href="/"><img src="../../assets/images/logo-mini.svg" alt="logo"/></a>
    </div>
    <b-collapse is-nav id="nav_collapse">
      <b-navbar-nav class="header-links">
        <b-nav-item href="#" active><i class="mdi mdi-image-filter"></i>Portal</b-nav-item>
        <b-nav-item href="#"><i class="mdi mdi-email-outline"></i>Test</b-nav-item>
        <!--<b-nav-item href="#"><i class="mdi mdi-calendar"></i>Calendar</b-nav-item>-->
      </b-navbar-nav>
    </b-collapse>
  </b-navbar>
</template>

<script lang="js">
export default {
  name: 'app-header'
}
</script>

<style scoped lang="scss">
.app-header {
}
</style>
