<template>
  <!--<img alt="Vue logo" src="./assets/logo.png" />-->
  app vue

  变量名转换

  <!--<HelloWorld msg='Hello Vue 3 + TypeScript + Vite'/>-->
  <VarNameConvert></VarNameConvert>
</template>

<script lang='ts'>
import {defineComponent} from 'vue'
import HelloWorld from './components/HelloWorld.vue'
import VarNameConvert from './views/var-name-convert.vue'

export default defineComponent({
  name: 'App',
  components: {
    VarNameConvert
  }
})
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
