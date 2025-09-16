<template>
  <section class="portal">
    <h2>Portal</h2>
    <img src="@/assets/portal.jpg" alt="Portal portada" class="game-cover" />
    <p>
      Portal es un juego de lógica en primera persona creado por Valve. 
      Usa la pistola de portales para resolver acertijos, 
      mientras una inteligencia artificial llamada GLaDOS pone a prueba tu ingenio.
    </p>
    <button @click="verTrailer">Ver tráiler</button>
  </section>
</template>

<script>
export default {
  name: "Portal",
  methods: {
    verTrailer() {
      window.open("https://www.youtube.com/watch?v=TluRVBhmf8w", "_blank");
    }
  }
};
</script>

<style scoped>
.portal {
  text-align: center;
  margin: 2rem;
  padding: 1rem;
  border: 2px solid #3a8ee6;
  border-radius: 12px;
  background: #0d1b2a;
  color: #e0e0e0;
  font-family: 'Arial', sans-serif;
}

.game-cover {
  width: 250px;
  border-radius: 8px;
  margin: 1rem 0;
  box-shadow: 0 0 12px #3a8ee6;
}

button {
  background: #3a8ee6;
  color: #fff;
  border: none;
  padding: 10px 20px;
  margin-top: 1rem;
  border-radius: 6px;
  cursor: pointer;
  font-weight: bold;
  transition: 0.3s;
}

button:hover {
  background: #2a6cb3;
}
</style>
