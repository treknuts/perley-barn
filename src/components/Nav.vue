<template>
  <div id="nav">
    <img alt="Barn" src="../assets/Barn-01.svg" />
    <div class="navbar-nav">
      <router-link to="/">Home</router-link> |
      <router-link to="/about">About</router-link> |
      <router-link to="/book">Book</router-link>
    </div>
  </div>
</template>

<script>
export default {
  name: "Nav",
};
</script>

<style scoped>
#nav {
  padding: 1em;
  position: fixed;
  top: 0;
  height: 2em;
  width: 100vw;
  background: #fdf6e4;
  color: #b55942;
  display: flex;
  align-items: center;
  box-shadow: rgba(0, 0, 0, 0.24) 0px 3px 8px;
  /* box-shadow: rgba(50, 50, 93, 0.25) 0px 50px 100px -20px,
    rgba(0, 0, 0, 0.3) 0px 30px 60px -30px,
    rgba(10, 37, 64, 0.35) 0px -2px 6px 0px inset; */
}

#nav a {
  font-weight: bold;
  text-decoration: none;
  color: #b55942;
  margin-inline: 2em;
}

#nav a:last-child {
  margin-right: 3em;
}

#nav a.router-link-exact-active {
  color: #b4482d;
}

#nav img {
  width: 4rem;
  height: auto;
}
</style>
