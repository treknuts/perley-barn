<template>
  <div class="book">
    <h1>{{ msg }} &#x1F60A;</h1>
  </div>
</template>

<script>
export default {
  name: "BookForm",
  props: {
    msg: String,
    emote: String,
  },
};
</script>

<style scoped>
.book {
  width: 100%;
  height: 100%;
  display: flex;
  justify-content: center;
  align-items: center;
}

h1 {
  padding: 0;
  margin: 0;
  color: #42b983;
}
</style>
