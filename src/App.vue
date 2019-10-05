<template>
  <div id="app"><!--
    <img src="./assets/logo.png">
    <div>
      <p>
        If iView is successfully added to this project, you'll see an
        <code v-text="'<Button>'"></code>
        below
      </p>
      <van-button type="primary">Button</van-button>
    </div>
    <HelloWorld msg="Welcome to Your Vue.js App" />-->
    <ToBar/>
  </div>
</template>

<script>
import ToBar from '@/components/ToBar.vue'
export default {
  name: 'app',
  components: {
    ToBar
  }
}
</script>

<style>
#app {
  font-family: "Avenir", Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
</style>
