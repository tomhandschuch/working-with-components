<template>
  <HeaderMan />
  <main>
    <div id="app" class="inside">
      <BookList />
    </div>
  </main>
</template>

<script>
import HeaderMan from "./components/HeaderMan.vue";
import BookList from "./components/BookList.vue";

export default {
  name: "App",
  components: {
    HeaderMan,
    BookList,
  },
};
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
