<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <h2>{{ email }}</h2>
    <a
      href="http://www.zhaoxiao.vip"
      target="_blank"
    >
      打开自己
    </a>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  data () {
    return {
      msg: 'Welcome XiaoXiao',
      email: '1666666666'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
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
