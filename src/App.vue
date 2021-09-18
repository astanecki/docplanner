<template>
  <div id="app">
    <Header />
    <LinkPage />
  </div>
</template>

<script>
import LinkPage from '@/pages/link/Link.page';
import Header from '@/design/patterns/header/Header';

export default {
  name: 'App',
  components: {
    Header,
    LinkPage
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  
  color: #2c3e50;
  background-color: rgb(237, 239, 242);
}
</style>
