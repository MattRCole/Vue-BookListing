<template>
  <div id="app">
    <img src="./assets/logo.png">
    <book-list>
      <h1>
        <li>1</li>
        <li>2</li>
        <li>3</li>
      </h1>
    </book-list>
  </div>
</template>

<script>
import BookList from './components/BookList';

export default {
  name: 'app',
  components: {
    BookList,
  },
};
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
