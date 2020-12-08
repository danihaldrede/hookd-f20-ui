<template>
    <div id="app">
        <div id="nav">
            <router-link to="/">Home</router-link>
            <router-link to="/">About</router-link>
        </div>
        <router-view/>
        <b-navbar fixed="bottom" type="dark" variant="info">
            <b-navbar-nav class="mx-auto" align="center">
                <b-nav-item to="Profile">
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
                <b-nav-item to="FishLog">
                    <b-icon-map-fill /><br>
                    FishLog
                </b-nav-item>
            </b-navbar-nav>
        </b-navbar>
    </div>
</template>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

#nav {
  padding: 30px;

  a {
    font-weight: bold;
    color: #2c3e50;

    &.router-link-exact-active {
      color: #42b983;
    }
  }
}
</style>
