<template>
  <div class="navbar-fixed">
    <nav class="white nav" role="navigation">
      <div class="nav-wrapper container">
        <a id="logo-container" href="#" class="brand-logo black-text">0e1dev</a>
        <ul class="right">
          <li><a href="#" class="black-text"> <i class="material-icons left">home</i> Home</a></li>
        </ul>
      </div>
    </nav>
  </div>
</template>

<script>
export default {
  name: 'navbar',
  data () {
  }
}
</script>

<style scoped>
  .nav {
    background: rgba(255,255,255,0.5);
    box-shadow: 1px 1px 1px rgba(0,0,0,0.1) !important;
  }
</style>