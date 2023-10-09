<template>
    <div class="jumbotron boolean-bg text-center">
      <div class="hero-content">
        <h1 class="display-4 text-green boolean-text animated fadeInUp">
          WELCOME TO THE <span class="text-red">BOOLEAN</span>
        </h1>
        <p class="text-muted lead animated fadeInLeft">
          <span class="text-blue">Lorem ipsum dolor sit amet consectetur adipisicing elit. Repudiandae, commodi!</span>
        </p>
        <hr class="my-4">
        <p class="text-muted animated fadeInRight">
            <span class="text-cyan">Try coding experience</span>
        </p>
        <a href="#" class="btn btn-lg btn-danger mt-4 animated pulse">Enter the <span class="text-green">Team</span></a>
      </div>
    </div>
</template>
  
<script>
export default {
    name: 'AppHero'
}
</script>
  
<style scoped>
/* Stili CSS specifici per il componente AppHero */
.boolean-bg {
    background: linear-gradient(to bottom, rgba(0,0,0,0.8), rgba(0,0,0,0.9)), url('/src/assets/img/img.jpg');
    background-size: cover;
    background-position: center;
    background-blend-mode: overlay; /* Sovrapponi il testo con lo sfondo */
    color: #00FF00; /* Testo verde */
    padding: 4rem 0;
    border-radius: 0;
}
  
.hero-content {
    max-width: 800px;
    margin: 0 auto;
}
  
/* Stile per il titolo principale */
.display-4 {
    font-size: 4rem;
    font-weight: bold;
}
  
/* Stile per il testo del jumbotron */
.text-muted {
    font-size: 1.5rem;
}
  
/* Stile per il testo "boolean" */
.boolean-text {
    font-size: 6rem;
    letter-spacing: 10px;
    font-family: 'Orbitron', sans-serif;
}
  
/* Stile per il pulsante */
.btn-danger {
    background-color: #FF0000; /* Cambia il colore del pulsante a rosso */
    border-color: #FF0000; /* Cambia il colore del bordo del pulsante a rosso */
    font-size: 1.5rem;
    font-weight: bold;
}
  
/* Stili per le varie sfumature rgba */
.text-red { 
    color: rgba(255, 0, 0, 0.8); 
}
.text-blue { 
    color: rgba(0, 0, 255, 0.8); 
}
.text-cyan {
    color: rgba(0, 255, 255, 0.8); 
}
.text-green { 
    color: rgba(0, 255, 0, 0.8); 
}
</style>
  