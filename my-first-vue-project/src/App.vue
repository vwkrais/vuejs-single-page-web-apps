<template>
  <ListHeader />
  <div id="app" class="inside">
    <BookList />
  </div>
</template>

<script>
import ListHeader from "./components/ListHeader.vue";
import BookList from "@/components/BookList.vue";

export default {
  name: "App",
  components: {
    ListHeader,
    BookList,
  },
};
</script>

<style>
@import url("./assets/global.css");
</style>
