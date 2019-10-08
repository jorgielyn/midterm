<template>
  <div id="app">
    <Header></Header>
    <!-- <img alt="Vue logo" src="./assets/logo.png">
    <HelloWorld msg="Welcome to Your Vue.js App"/> -->
  </div>
</template>

<script>
//import HelloWorld from './components/HelloWorld.vue'
import Header from './components/frame/Header.vue'
//import login from './components/Form/login.vue'

export default {
  name: 'app',
  components: {
    Header
  }
}

</script>

