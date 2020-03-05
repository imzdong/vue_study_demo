<!--模板记载在App里面-->
<template>
    <h1>{{ msg }}</h1>
</template>
<!--js-->
<script>
export default {
  name: 'demo01',
  /*数据*/
  data () {
    return {
      msg: '我是demo01'
    }
  }
}
</script>

<!-- 样式 -->
<style scoped>
h1, h2 {
  font-weight: normal;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
