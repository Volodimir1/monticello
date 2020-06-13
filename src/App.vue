<template>
  <div id="app">
    <Header/>
  </div>
</template>

<script>
import Header from './components/Header'

export default {
  name: 'App',
  components: {
    Header
  }
}
</script>

// <style lang="scss">
@font-face {
  font-family: GothamBlack;
  src: url(fonts/Gotham-Black.otf);
  font-weight: normal;
  font-style: normal;
}
@font-face {
  font-family: GothamBook;
  src: url(fonts/GothamBook.ttf);
  font-weight: normal;
  font-style: normal;
}
#app {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  scroll-behavior: smooth;
}
</style>
