<template>
  <div class="topbar">
    <div class="header">
      <button id="btn-bar" class="btn text-light" @click="open_bar">
        <i class="fas fa-bars"></i>
      </button>
    </div>
  </div>
</template>

<script>
export default {
  name: 'TopBar',
  methods: {
    open_bar: function () {
      document.getElementById('side-bar').style.width = '25%'
      document.getElementById('side-bar').style.display = 'block'
      document.getElementById('btn-bar').style.display = 'none'
    }
  }
}
</script>

<style></style>
