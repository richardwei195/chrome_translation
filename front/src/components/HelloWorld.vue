<template>
  <div class="hello">
    <el-input v-model="input" placeholder="请输入内容"></el-input>
    <el-input type="textarea"></el-input>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  data () {
    return {
      msg: 'Welcome to Your Vue.js App'
    }
  },
  mounted() {
    this.$message('这是一条消息提示');
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.class {
  width: 1200px;
  height: 60px;
  background: black
}
</style>
