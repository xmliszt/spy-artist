<template>
  <div id="app">
    <router-view />
  </div>
</template>

<style>
body {
  cursor: url(https://cur.cursors-4u.net/others/oth-5/oth510.ani),
    url(http://cur.cursors-4u.net/others/oth-5/oth510.png), default !important;
}

#app {
  font-family: "Gill Sans", "Gill Sans MT", Calibri, "Trebuchet MS", sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

.el-button,
.el-button:hover,
.el-button:focus {
  cursor: url(https://cur.cursors-4u.net/others/oth-5/oth510.ani),
    url(http://cur.cursors-4u.net/others/oth-5/oth510.png), default !important;
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
