<template>
  <div id="app">
    <Header />
    <Menu />
    <main>
      <section id="darksouls"><Darksouls /></section>
      <section id="portal"><Portal /></section>
      <section id="hollow"><HollowKnight /></section>
    </main>
    <Footer />
  </div>
</template>

<script>
import Header from './components/Header.vue'
import Menu from './components/Menu.vue'
import Darksouls from './components/Darksouls.vue'
import Portal from './components/Portal.vue'
import HollowKnight from './components/HollowKnight.vue'
import Footer from './components/Footer.vue'

export default {
  components: { Header, Menu, Darksouls, Portal, HollowKnight, Footer }
}
</script>