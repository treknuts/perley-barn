<template>
  <div id="app">
    <Nav />
    <router-view class="content" />
  </div>
</template>

<script>
import Nav from "./components/Nav";

export default {
  components: {
    Nav,
  },
};
</script>
