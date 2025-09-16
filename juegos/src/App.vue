<template>
  <div>
    <h1>Pagina de nuestros juegos favoritos</h1>
    <Darksouls />
    <Portal />
  </div>
</template>

<script>
import Darksouls from './components/Darksouls.vue'
import Portal from './components/Portal.vue'

export default {
  components: { Darksouls, Portal }
}
</script>


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
