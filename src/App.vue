<template>
  <div id="app" >
    <Header id="header"></Header>
    <v-container id="main">
      <Top></Top>
    </v-container>
    <v-container id="footer">
    </v-container>
  </div>
</template>

<script>
//import Unavailable from './views/Unavailable.vue'
//import Home from './views/Home.vue'
//import Impressum from './components/Impressum.vue'
import Header from './components/Header.vue'
import Top from './components/Top.vue'

export default {
  name: 'App',
  components: {
    Header,
    Top
    //Unavailable,
    //Home,
    //Impressum,
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
}
</style>


<style>
:root {
    --kkb-green: rgba(175, 230, 91, 1.0)
}
</style>
