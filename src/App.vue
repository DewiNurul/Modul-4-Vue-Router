<template>
  <div id="app">
    
    <ul class="nav" style="background-color: #e3f2fd">
      <li class="nav-item"><router-link class="nav-link" to="/">Home</router-link></li>
      <li class="nav-item"><router-link class="nav-link" to="/about">About</router-link></li>
      <li class="nav-item"><router-link class="nav-link" to="/contact">Contact</router-link></li>
    </ul>

    <router-view></router-view>
  </div>
</template>

<script>
// import Home from './components/Home.vue'
// import About from './components/About.vue'
// import Contact from './components/Contact.vue'
// import NotFound from './components/import NotFound.vue'

export default {
  name: 'App',
  components: {
    // Home,
    // About,
    // Contact,
    // NotFound
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
