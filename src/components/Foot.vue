<template>
  <footer>
    Made by <a href="http://pereiraryan.github.io">Ryan Pereira</a>
    //
    See <a href="https://www.github.com/pereiraryan">LogicBoxes on Github</a>.
  </footer>
</template>

<script>
  export default {
    name: 'Foot'
  }
</script>

<style scoped lang="scss">
  footer {
    text-align: center;
    padding: 1rem;
    background: $gray--light;
  }

  a {
    font-weight: bold;
  }
</style>
