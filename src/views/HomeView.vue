<template>
  <div id="home" class="main d-flex flex-column justify-center align-center">
    <h1 style="font-family: Garamond, serif !important; letter-spacing: 2px" class="text-h1">
      Opportunities don't happen<br />You create them
    </h1>
    <p>-Logan G. Gibson</p>
  </div>
</template>
<style scoped>
.main {
  background: url('../assets/images/black.png');
  background-size: cover;
  width: 100vw;
  height: 80vh;
  color: white;
}
</style>
<script>
export default {
  watch: {
    '$route.params.id': {
      handler: function (id) {
        if (id) {
          this.goTo(id)
        } else {
          window.scrollTo(0, 0)
        }
      },
      deep: true,
      immediate: true
    }
  },
  methods: {
    goTo(id) {
      if (id == 'about') {
        document.getElementById(id).scrollIntoView()
      }
    }
  }
}
</script>
