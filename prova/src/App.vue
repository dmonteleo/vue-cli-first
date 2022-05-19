<template>
  <div id="app">
    <Header />
    <Main />
    <Footer />
    <header>
      Questo è l'header
    </header>
    <main>
      Questo è il main
    </main>
    <footer>
      Questo è il footer
    </footer>
  </div>
</template>

<script>
import Header from './components/Header.vue'
import Main from './components/Main.vue'
import Footer from './components/Footer.vue'

export default {
  name: 'App',
  components: {
    Header: Header,
    Main: Main, 
    Footer: Footer
  }
}
</script>

<style scoped>
header {
  background-color: green;
}
</style>
