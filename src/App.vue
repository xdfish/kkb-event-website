<template>
  <div id="app" >
    <Header id="header"></Header>
    <v-container id="main">
      <Top id="top"></Top>
    </v-container>
    <v-container id="footer">
    </v-container>
  </div>
</template>

<script>

import Header from './components/Header.vue'
import Top from './components/Top.vue'

export default {
  name: 'App',
  components: {
    Header,
    Top
  }
}

</script>


<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  background: black;
}
#header{
  position: relative;
  z-index: 2;
}
#top{
  position: relative;
  z-index: 1;
}
</style>


<style>
:root {
    --kkb-green: rgba(175, 230, 91, 1.0)
}
</style>
