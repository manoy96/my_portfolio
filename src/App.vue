<template>
  <div id="app">
    <!-- <div id="nav">
      <router-link to="/">Home</router-link> |
      <router-link to="/about">About</router-link> |
      <router-link to="/work">Work</router-link>
    </div>-->
    <v-toolbar>
      <v-toolbar-side-icon></v-toolbar-side-icon>
      <v-toolbar-title>Title</v-toolbar-title>
      <v-spacer></v-spacer>
      <v-toolbar-items class="hidden-sm-and-down">
        <v-btn flat to="/">Link One</v-btn>
        <v-btn flat to="/about">Link Two</v-btn>
        <v-btn flat to="/work">Link Three</v-btn>
        <!-- <v-btn flat><router-link to="/">Home</router-link></v-btn>
        <v-btn flat><router-link to="/about">About</router-link></v-btn>
        <v-btn flat><router-link to="/work">Work</router-link></v-btn> -->
      </v-toolbar-items>
    </v-toolbar>

    <router-view/>
  </div>
</template>

<style>
#app {
  font-family: "Avenir", Helvetica, Arial, sans-serif;
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
