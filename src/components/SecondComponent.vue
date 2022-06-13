<template>
  <div class="hello">
      <h3>My Second VUE CLI component</h3>

  </div>
</template>

<script>
export default {
  name: 'MyTitle',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3{
    color: green;
}
</style>
