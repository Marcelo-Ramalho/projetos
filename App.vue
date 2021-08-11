<template>
  <div id="app">

    <Header/>
      <Pesquisa/>
        <Asidebar/>
  </div>
</template>

<script>
import Header from './components/Header.vue'
import Pesquisa from './components/Pesquisa.vue'
import Asidebar from './components/Asidebar.vue'

export default {
  name: 'App',
  components: {
    Header,
    Pesquisa,
    Asidebar
  }
}
</script>

<style>
* {
  margin: 0;
  padding: 0cd;
}

</style>
