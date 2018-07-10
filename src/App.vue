<template>
  <div id="app">
    <hello></hello>
  </div>
</template>

<script>
import layui from '../static/lib/layui-v2.3.0/layui/layui.js'
import '../static/lib/layui-v2.3.0/layui/css/layui.css'
import '../static/css/main.css'
import Hello from './components/Hello'

export default {
  name: 'app',
  components: {
    Hello
  }
}
</script>

<style>
</style>
