<template>
  <div id="nav">
    <div class="nav"><router-link to="/resume">Resume</router-link></div>
    <div class="nav"><router-link to="/">Portfolio</router-link></div>
    <div class="nav"><router-link to="/about">About</router-link></div>
    <router-view />
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
#nav {
  padding: 30px;
  text-align: center;
}

#nav a {
  font-weight: bold;
  text-decoration: none;
  color: #000;
  border-radius: 5px;
}

#nav a:hover {
  color: #fff;
  border-bottom: solid 3px;
}

#nav a.router-link-exact-active {
  color: #ffffff;
  border: solid 3px;
  padding: 3px;
}
.nav {
  display: inline-block;
  margin: 1%;
}
</style>