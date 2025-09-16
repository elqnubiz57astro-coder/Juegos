<template>
  <div id="app">
    <!-- Encabezado -->
    <Header />

    <!-- Menú de navegación -->
    <Menu />

    <!-- Contenido principal -->
    <main>
      <section id="darksouls">
        <Darksouls />
      </section>

      <section id="portal">
        <Portal />
      </section>
    </main>

    <!-- Pie de página -->
    <Footer />
  </div>
</template>

<script>
import Header from './components/Header.vue'
import Menu from './components/Menu.vue'
import Darksouls from './components/Darksouls.vue'
import Portal from './components/Portal.vue'
import Footer from './components/Footer.vue'

export default {
  name: "App",
  components: {
    Header,
    Menu,
    Darksouls,
    Portal,
    Footer
  }
}
</script>

<style>
/* Estilos generales */
#app {
  font-family: 'Arial', sans-serif;
  background: #0d0d0d;
  color: #f1f1f1;
  min-height: 100vh;
}

main {
  padding: 2rem;
}
</style>



<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
