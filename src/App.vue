<template>
  <div id="app">
    <Navbar></Navbar>
    <router-view></router-view>
  </div>
</template>

<script>
import Home from './components/Home'
import Login from './components/Login'
import Navbar from './components/Navbar'

export default {
  name: 'app',
  components : {
    Navbar
  },
  data () {
    return {
    }
  }
}
</script>

<style>
</style>
