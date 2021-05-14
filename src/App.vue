<template>
  <div id="app">
    <div id="nav">
      <img alt="Barn" src="./assets/Barn-01.svg" />
      <div class="navbar-nav">
        <router-link to="/">Home</router-link> |
        <router-link to="/about">About</router-link> |
        <router-link to="/book">Book</router-link>
      </div>
    </div>
    <router-view class="content" />
  </div>
</template>
