<template>
  <!-- <img alt="Vue logo" src="./assets/logo.png"> -->

  <div>
    <!--v-code-diff -->
  <AnotherDiffViewTest/>

<!--vue-diff -->
    <DiffViewTest />
  </div>

<!-- 
  <HelloWorld msg="Welcome to Your Vue.js App"/> -->
</template>

<script>
// import HelloWorld from './components/HelloWorld.vue'
import AnotherDiffViewTest from './components/AnotherDiffViewTest.vue';
import DiffViewTest from './components/DiffViewTest.vue';

export default {
  name: 'App',
  components: {
    // HelloWorld,
    AnotherDiffViewTest,
    DiffViewTest
  }
}
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
