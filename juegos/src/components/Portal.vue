<template>
  <section class="games">
    <h2>Favoritos de Puzzle & Aventura</h2>

    <!-- Portal -->
    <div class="game-card">
      <h3>Portal</h3>
      <img src="@/assets/portal.jpg" alt="Portal portada" class="game-cover" />
      <p>
        Portal es un juego de lógica en primera persona creado por Valve. 
        Usa la pistola de portales para resolver acertijos, 
        mientras una inteligencia artificial llamada GLaDOS pone a prueba tu ingenio.
      </p>
      <button @click="verTrailer('portal')">Ver tráiler</button>
    </div>

    <!-- The Legend of Zelda: Breath of the Wild -->
    <div class="game-card">
      <h3>The Legend of Zelda: Breath of the Wild</h3>
      <img src="@/assets/zelda.jpg" alt="Zelda Breath of the Wild portada" class="game-cover" />
      <p>
        Breath of the Wild es una aventura de mundo abierto desarrollada por Nintendo. 
        Explora Hyrule con libertad, resuelve acertijos, enfrenta enemigos 
        y descubre secretos en un vasto y bello entorno.
      </p>
      <button @click="verTrailer('zelda')">Ver tráiler</button>
    </div>
  </section>
</template>

<script>
export default {
  name: "Portal",
  methods: {
    verTrailer(juego) {
      if (juego === "portal") {
        window.open("https://www.youtube.com/watch?v=TluRVBhmf8w", "_blank"); // Portal trailer
      } else if (juego === "zelda") {
        window.open("https://www.youtube.com/watch?v=zw47_q9wbBE", "_blank"); // Zelda BOTW trailer
      }
    }
  }
};
</script>

<style scoped>
.games {
  text-align: center;
  margin: 2rem auto;
  max-width: 900px;
  padding: 1rem;
}

.game-card {
  border: 2px solid #3a8ee6;
  border-radius: 12px;
  background: #0d1b2a;
  color: #e0e0e0;
  font-family: 'Arial', sans-serif;
  padding: 1rem;
  margin: 1.5rem 0;
  box-shadow: 0 0 12px rgba(58, 142, 230, 0.6);
}

.game-card h3 {
  margin-bottom: 0.5rem;
  color: #3a8ee6;
}

.game-cover {
  width: 300px;
  border-radius: 8px;
  margin: 1rem 0;
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