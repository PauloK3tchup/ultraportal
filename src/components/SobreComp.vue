<template>
  <div class="container-fluid">
    <div class="artigo">
      <img class="esquerda" src="../assets/img/Ultrakill_cover.png" alt="" />
      <p>
        ULTRAKILL é um jogo de ação FPS old school criado por Arsi "Hakita" Patala e distribuído
        pela New Blood Interactive que está, atualmente, em desenvolvimento ativo. O jogo é
        conhecido por ser
        <span class="negrito">MUITO</span> rápido e violento, sua ação é constante e o jogo
        dificilmente desacelera durante as fases. Inspirado em jogos como DOOM e Quake, o jogo
        possui um estilo low-poly que, apesar de suas limitações, se mostra muito efetivo durante a
        gameplay.
      </p>
    </div>
    <div class="foto">
      <img class="direita" src="../assets/img/tenebre-rosso-sangue-capa.jpg" alt="" />
    </div>
  </div>
</template>
<style scoped>
div.artigo {
  margin: 35px;
  padding: 20px;
  background-color: #800000;
  border-radius: 10px;
  margin-top: 100px;
  margin-bottom: 100px;
  width: 60%;
  display: flex;
}

div.artigo p {
  font-family: VCR;
  display: inline-block;
  vertical-align: top;
  font-size: 20px;
  text-align: justify;
}

div.artigo h1 {
  font-family: BroshK;
  display: inline-block;
  vertical-align: top;
  font-size: 50px;
}

.negrito {
  font-weight: bolder;
}

img.esquerda {
  margin-right: 20px;
  display: inline-block;
}

div.esquerda {
  display: inline-block;
}

div.foto {
  width: 40%;
  display: inline-block;
  margin-top: 100px;
  margin-bottom: 100px;
  padding: 20px;
}

img.direita {
  width: 400px;
  height: auto;
  align-self: center;
}

.container-fluid {
  display: flex;
  width: 100%;
}
</style>
