<template>
  <div class="book">
    <img alt="Vue logo" src="../assets/logo.png" />
    <BookForm msg="Book the venue for your wedding here!" />
  </div>
</template>

<script>
// @ is an alias to /src
import BookForm from "@/components/BookForm.vue";

export default {
  name: "Book",
  components: {
    BookForm,
  },
};
</script>
