<!--
 * @Author: your name
 * @Date: 2019-11-07 18:53:32
 * @LastEditTime: 2019-11-15 11:02:14
 * @LastEditors: Please set LastEditors
 * @Description: In User Settings Edit
 * @FilePath: \coexisting-vue-microfrontends-master\app2\src\components\HelloWorld.vue
 -->
<template>
  <div class="hello">
    <router-link to="/app2/about">Go to appfds2aaa about page</router-link>
  </div>
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
h3 {
  margin: 40px 0 0;
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
