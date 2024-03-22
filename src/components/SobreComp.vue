<template>
  <a class="anchor2" id="sobre"></a>
  <div class="container-fluid">
    <div v-motion-slide-visible-left class="artigo">
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
    <div v-motion-slide-visible-right class="foto">
      <img class="direita" src="../assets/img/tenebre-rosso-sangue-capa.jpg" alt="" />
    </div>
  </div>
  <div class="mais-info branco">
    <h1 v-motion-slide-visible-right class="negrito">Mas sobre o que é o jogo?</h1>
    <br />
    <p v-motion-slide-visible-left>
      <span class="ultratexto-mini">A Humanidade morreu</span>
      <br />
      <span class="ultratexto-mini">O Sangue é combustível</span>
      <br />
      <span class="ultratexto-mini negrito">O Inferno está cheio</span>
      <br />
      <br />
      Máquinas movidas a sangue foram criadas para lutar em guerras, mas a humanidade perdeu o
      controle e logo cada pingo de sangue do planeta foi consumido. Com a extinção da vida na
      terra, as máquinas ficaram sem sua fonte de combustível, mas não por muito tempo, pois elas
      descobriram outro lugar com bastante sangue para consumir:
      <span class="vermelho negrito">o Inferno</span>. <br />
      No jogo você controla V1, o protótipo mais avançado dessas máquinas, avançando pelas múltiplas
      camadas do Inferno em busca de sangue para saciar sua fome interminável. Use das mais variadas
      armas e habilidades para destruir seus inimigos do jeito mais estiloso possível para ganhar
      pontos e humilhar as criaturas que ousarem cruzar seu caminho. Massacre demônios, anjos e
      todas as outras criaturas que se escondem nesse palácio de dor e sofrimento. <br />
      <br />
      <span class="ultratexto-mini">O Inferno nunca foi tão divertido!</span>
    </p>
  </div>
  <div class="mais-info preto">
    <h1 v-motion-slide-visible-right class="negrito">E como ele é jogado?</h1>
    <br />
    <p v-motion-slide-visible-left>
      bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla
      bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla
      bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla
      bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla
      bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla
      bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla
      bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla
      bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla
      bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla
      bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla
      bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla
      bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla
      bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla
      bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla
      bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla
      bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla
      bla bla bla bla bla bla bla bla bla bla
    </p>
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
  width: 50%;
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
  width: 50%;
  display: inline-block;
  text-align: center;
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

div.mais-info {
  padding: 50px;
  font-family:
    Inter,
    -apple-system,
    BlinkMacSystemFont,
    'Segoe UI',
    Roboto,
    Oxygen,
    Ubuntu,
    Cantarell,
    'Fira Sans',
    'Droid Sans',
    'Helvetica Neue',
    sans-serif;
}

.branco {
  color: black;
  background-color: rgb(255, 255, 255);
}

.preto {
  color: white;
  background-color: rgb(0, 0, 0);
}
</style>
