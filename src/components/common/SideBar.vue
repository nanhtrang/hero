<template>
  <div class="sidebar col-2 bg-dark p-0 h-100" id="side-bar">
    <div class="col-12 p-0">
      <div class="col-12 p-0">
        <button class="btn text-light w-100" @click="close_bar">
          <i class="fas fa-bars"></i>
        </button>
      </div>
      <div class="col-12 p-0">
        <a href="#" class="btn w-100 text-light">Link 1</a>
      </div>
      <div class="col-12 p-0">
        <a href="#" class="btn w-100 text-light">Link 2</a>
      </div>
      <div class="col-12 p-0">
        <a href="#" class="btn w-100 text-light">Link 3</a>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'SideBar',
  methods: {
    close_bar: function () {
      document.getElementById('side-bar').style.display = 'none'
      document.getElementById('btn-bar').style.display = 'inline-block'
    }
  }
}
</script>

<style>

</style>
