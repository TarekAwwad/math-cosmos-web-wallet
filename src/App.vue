<template>
  <div id="app">
    <web-nav></web-nav>
    <router-view/>
    <footer class="copyright">© 2020</footer>
  </div>
</template>

<script>
import webNav from '@/base/nav'
export default {
  name: 'App',
  components: {
    webNav
  }
}
</script>

<style>

</style>
