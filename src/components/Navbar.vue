<template>
  <div class="navbar-fixed">
    <nav class="white nav" role="navigation">
      <div class="nav-wrapper container">
        <a id="logo-container" href="#" class="brand-logo black-text">0e1dev</a>
        <ul class="right">
          <li><a href="#" class="black-text">Home</a></li>
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
    background: rgba(255,255,255,0.7) !important;
    box-shadow: none !important;
  }
  .brand-logo {
    font-family: 'Nova Mono', monospace;
    font-size: 44px;
  }
  a {
    font-family: 'Nova Mono', monospace;
    font-size: 18px;
  }
</style>