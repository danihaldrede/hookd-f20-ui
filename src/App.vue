// nav bar
<template>
    <div id="app">
        <div id="nav">
            <router-link to="/">Home  </router-link>
            <router-link to="/about">About   </router-link>
            <router-link to="/login">Login   </router-link>
        </div>
        <router-view/>
        <b-navbar fixed="bottom" type="dark" variant="success">
            <b-navbar-nav class="mx-auto" align="center">
                <b-nav-item to="/profile">
                    <b-icon-person-circle/><br>
                    Profile
                </b-nav-item>
                <b-nav-item to="Weather">
                    <b-icon-sun /><br>
                    Weather
                </b-nav-item>
                <b-nav-item to="/">
                    <b-icon icon="house-fill"/><br>
                    Home
                </b-nav-item>
                <b-nav-item to="Journal">
                    <b-icon-journals /><br>
                    Journal
                </b-nav-item>
                <b-nav-item to="/fish">
                    <b-icon-map-fill /><br>
                    Fish
                </b-nav-item>
            </b-navbar-nav>
        </b-navbar>
    </div>
</template>

<script>
// @ is an alias to /src
export default {
  name: 'Home'
}
</script>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #0d6b22;
}

#nav {
  padding: 30px;

  a {
    font-weight: bold;
    color: #05530b;

    &.router-link-exact-active {
      color: #42b983;
    }
  }
}
</style>
