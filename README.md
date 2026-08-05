<h1 class="rainbow-text">Gemini</h1>

<style>
.rainbow-text {
  font-size: 4rem;
  font-weight: 800;
  font-family: sans-serif;
  
  /* 1. Gradiente repetido para transição suave */
  background: linear-gradient(
    90deg, 
    #ff0000, #ff7f00, #ffff00, #00ff00, #00ffff, #0000ff, #8b00ff, #ff0000
  );
  
  /* 2. Expande o fundo para permitir o deslocamento da animação */
  background-size: 200% auto;
  
  /* 3. Recorta o fundo no formato do texto */
  -webkit-background-clip: text;
  background-clip: text;
  
  /* 4. Torna o texto transparente para revelar o gradiente atrás */
  -webkit-text-fill-color: transparent;
  color: transparent;
  
  /* 5. Animação contínua e suave */
  animation: rainbowScroll 4s linear infinite;
}

@keyframes rainbowScroll {
  0% {
    background-position: 0% center;
  }
  100% {
    background-position: 200% center;
  }
}
</style>
