<template>
  <v-container class="home">
    <h1 >Welcome to the HOME!</h1>
  </v-container>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.home {
  font-family: 'Courier New', Courier, monospace;
  background-color: dodgerblue;
}
</style>
