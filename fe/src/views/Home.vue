<template>
  <div name="home">
    <p>{{msg}}</p>
    <router-link to="/hello">
      <el-button type="primary">Hello</el-button>
    </router-link>
  </div>
</template>

<script>
export default {
  name: 'home',
  data () {
    return {
      msg: 'Welcome to Your Vue.js App'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

</style>
