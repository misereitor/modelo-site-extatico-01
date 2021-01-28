<template>
  <div id="app">
    <Header />
    <Conteiner />
    <Footer />
  </div>
</template>

<script>
import Header from "./components/header"
import Footer from "./components/footer"
import Conteiner from "./components/conteiner"
export default {
  name: 'App',
  components: {
    Header,
    Footer,
    Conteiner
  }
}
</script>

<style>
*{
  margin: 0;
  padding: 0;
  border: 0;
  font-family: 'Roboto', sans-serif;
}
</style>
