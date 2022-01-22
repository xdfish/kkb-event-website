<template>
  <div id="app" >
    <Header id="header"></Header>
    <div id="main">
      <Top id="top"></Top>
      <Over></Over>
    </div>
    <v-container id="footer">
    </v-container>
  </div>
</template>

<script>

import Header from './components/Header.vue'
import Top from './components/Top.vue'
import Over from './components/Over.vue'

export default {
  name: 'App',
  components: {
    Header,
    Top,
    Over,
  }
}

</script>


<style>
*{
  margin: 0;
}
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
#header{
  position: relative;
  z-index: 2;
}
#main {
  height:500px;
  overflow-y: auto;
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
