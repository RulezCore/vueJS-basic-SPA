<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <p>Welcome to test component</p>
    <hr>
  </div>
</template>

<script>
export default {
  name: 'Test',
  data () {
    return {
      msg: 'Component Test'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

</style>
