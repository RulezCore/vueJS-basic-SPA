<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <p>Welcome home component</p>
    <hr>
  </div>
</template>

<script>
export default {
  name: 'Home',
  data () {
    return {
      msg: 'Home Component'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

</style>
