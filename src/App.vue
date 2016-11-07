<template>
  <div id="app">
    <navbar></navbar>

    <div class="container">

      <div class="row">

        <div class="col s12 m7 l8">
          <recent-posts></recent-posts>
        </div> <!-- .col -->

        <div class="col s12 m5 l4">
          <sidebar></sidebar>
        </div> <!-- .col -->

      </div> <!-- row -->

    </div> <!-- .container -->

  </div> <!-- #app -->
</template>

<script>
import 'materialize-css/bin/materialize.css'
import 'animate.css'
import Navbar from './components/Navbar'
import RecentPosts from './components/RecentPosts'
import Sidebar from './components/Sidebar'

export default {
  name: 'app',
  components: {
    Navbar,
    RecentPosts,
    Sidebar
  }
}
</script>

<style>
</style>
