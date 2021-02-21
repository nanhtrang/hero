<template>
  <div id="app" class="bg-secondary">
    <div class="col-12 row">
      <side-bar></side-bar>
      <div class="main h-100">
        <top-bar></top-bar>
        <button class="btn btn-primary">a</button>
        <router-view />
      </div>
    </div>
    <!-- <img src="./assets/logo.png"> -->
  </div>
</template>

<script>
import SideBar from './components/common/SideBar.vue'
import TopBar from './components/common/TopBar.vue'
export default {
  name: 'App',
  components: { TopBar, SideBar }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #ffffff;
}
</style>
