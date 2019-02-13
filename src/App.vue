<template>
  <div id="app">
    <preloader />
    <navbar />
    <router-view></router-view>
    <page-footer/>
  </div>
</template>

<script>

import Preloader from './components/Preloader.vue'
import NavBar from './components/NavBar.vue'
import Footer from './components/Footer.vue'

export default {
  name: 'app',
  components: {
    'preloader': Preloader,
    'navbar': NavBar,
    'page-footer': Footer
  }
}
</script>
