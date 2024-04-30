<template>
  <div class="about">
    <div class="container">
      <div class="row">
        <div class="col-sm-12 col-md-6">
          <h1>Gustavo Longon Sobral</h1>
          <p><strong>Curso:</strong> Análise e Desenvolvimento de Sistemas</p>
          <p><strong>Local:</strong> Unimar, Marília/SP</p>
          <p>
            Sou um Desenvolvedor Front-End apaixonado por criar experiências digitais e tento sempre deixar uma marca positiva por onde passo. Sempre em busca de aprendizado contínuo, estou constantemente explorando novas tecnologias, afinal, a tecnologia avança rápido e é emocionante estar na linha de frente dessa evolução!
          </p>
          <h3>Confira meus últimos trabalhos:</h3>`
          <div class="row">
            <div class="col-4">
              <a href="https://redolfieferrari.adv.br/" target="_blank" class="card">
                <img src="/src/assets/img/site-1.jpg" alt="">
              </a>
            </div>
            <div class="col-4">
              <a href="https://murilomoreiraarquiteto.com.br/" target="_blank" class="card">
                <img src="/src/assets/img/site-2.jpg" alt="">
              </a>
            </div>
            <div class="col-4">
              <a href="https://eagleconstrutora.com.br/" target="_blank" class="card">
                <img src="/src/assets/img/site-3.jpg" alt="">
              </a>
            </div>
          </div>
        </div>
        <div class="col-sm-12 col-md-6">
          <img class="left__img" src="/src/assets/svg/vetor-about.svg" alt="">
        </div>
      </div>
    </div>
  </div>
</template>

<style>

.card {
  width: 100%;
  border-radius: 5px;
  padding: 3px;
  border: 5px solid #0ea8d5;
  overflow: hidden;
  transition: .3s;
}

.card:hover {
  transform: scale(.98);
}

.card img {
  width: 100%;
  height: 100%;
  object-fit: cover;
}

.left__img {
  width: 100%;
  height: auto;
}

@media (min-width: 1024px) {
  .about {
    min-height: 100vh;
    display: flex;
    align-items: center;
  }
}
</style>
