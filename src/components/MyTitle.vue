<template>
  <div class="hello">
      <h2>My first VUE CLI component</h2>

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
h2{
    color: red;
}
</style>
