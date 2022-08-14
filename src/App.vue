<template>
  <div id="app">
    <NavBar />
    <div class="container my-5">
      <div class="columns">
        <div class="column is-four-fifths">
            <router-view/>
        </div>
        <div class="column">
          <SideBar />
        </div>
      </div>
    </div>
    <Footer />
  </div>
</template>

<script>

import NavBar from './components/NavBar'
import SideBar from './components/SideBar'
import Footer from './components/Footer'

export default {
  components:{
    NavBar,
    SideBar,
    Footer
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
}

#nav {
  padding: 30px;
}

#nav a {
  font-weight: bold;
  color: #2c3e50;
}

#nav a.router-link-exact-active {
  color: #42b983;
}
</style>
