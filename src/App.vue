<script>

// IMPORT DEL COMPONENTE
import Header from "./components/Header.vue";
import Content from "./components/Content.vue";
import BlueBar from "./components/BlueBar.vue";
import UpperFooter from "./components/UpperFooter.vue";
import BottomFooter from "./components/BottomFooter.vue";

// DEFINIZIONE DEL COMPONENTE IN PAGINA
export default {

  components: {
    Header, Content, BlueBar, UpperFooter, BottomFooter
  },
};
</script>

<template>
  <Header></Header>
  <Content></Content>
  <BlueBar></BlueBar>
  <UpperFooter></UpperFooter>
  <BottomFooter></BottomFooter>
</template>

<style lang="scss">
/* PRESET */

*,
*::before,
*::after {
  box-sizing: border-box;
}

* {
  margin: 0;
  padding: 0;
  font: inherit;
}

body {
  min-height: 100vh;
}

img,
svg,
picture,
video {
  max-width: 100%;
}

/* Utils */

.container {
  max-width: 1000px;
  margin: 0 auto;
  display: flex;
}

ul {
  list-style: none;
}
</style>