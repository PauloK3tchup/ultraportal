<script setup>
import UltraVideo from '../components/VideoComp.vue'
import SobreComp from '../components/SobreComp.vue'
import CompOpcao from '@/components/CompOpcao.vue'
//import AnimatedComponent from '../components/AnimatedComponent.vue'
</script>

<template>
  <main>
    <UltraVideo />
    <a class="anchor2" id="sobre"></a>
    <SobreComp />
    <div class="mais-info branco">
      <h1 class="negrito">Mas sobre o que é o jogo?</h1>
      <p>
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
    <div class="mais-info preto">
      <h1 class="negrito">E como ele é jogado?</h1>
      <p>
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
    <div class="estrategias container-fluid">
      <a class="anchor2" id="strats"></a>
      <h1>Principais Estratégias</h1>
      <div class="botoes">
        <CompOpcao class="moedas sombra" texto="Moedas" />
        <CompOpcao class="pulo sombra" texto="Movimentação" />
        <CompOpcao class="probost sombra" texto="Outras" />
      </div>
    </div>
    <a class="anchor" id="speeds"></a>
    <div class="speedruns">
      <h1>Recordes atuais de speedruns</h1>
      <div class="coisos container-fluid">
        <div class="textospeed">
          <h1>Título Título bla bla</h1>
          <p>
            bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla
            bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla
            bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla
            bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla
            bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla
          </p>
        </div>
        <iframe
          class="iframe-speed"
          src="https://www.speedrun.com/ultrakill"
          frameborder="0"
        ></iframe>
      </div>
    </div>
    <div class="jogo">
      <h1>Gostou do jogo? Experimente a demo!</h1>
      <a href="https://devilmayquake.com/"
        >&#x3e;&#x3e;&#x3e; devilmayquake.com &#x3c;&#x3c;&#x3c;</a
      >
    </div>
  </main>
</template>
<style scoped>
div.jogo {
  background-color: white;
  color: black;
  text-align: center;
  padding: 30px;
}

div.jogo h1 {
  font-family: BroshK;
  font-size: 60px;
  text-align: center;
  color: black;
}

div.jogo a {
  font-family: VCR;
  font-size: 40px;
  text-align: center;
  color: rgb(153, 0, 0);
  text-decoration: none;
}

div.jogo a:hover {
  text-decoration: underline;
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

div.coisos {
  display: flex;
  justify-content: space-between;
}

div.estrategias {
  background-color: white;
  padding: 30px;
}

div.botoes {
  overflow: hidden;
  padding: 30px;
  display: flex;
  justify-content: space-between;
  align-items: center;
}

div.estrategias h1 {
  font-family: BroshK;
  font-size: 60px;
  text-align: center;
  color: black;
}

div.speedruns {
  padding: 30px;
}

div.textospeed {
  padding: 30px;
  width: 600px;
  display: inline-block;
}

div.speedruns p {
  font-family: VCR;
  font-size: 20px;
  text-align: center;
  color: rgb(255, 255, 255);
}

div.speedruns h1 {
  font-family: BroshK;
  font-size: 60px;
  text-align: center;
  color: rgb(255, 255, 255);
}

.branco {
  color: black;
  background-color: rgb(255, 255, 255);
}

.preto {
  color: white;
  background-color: rgb(0, 0, 0);
}

.iframe-speed {
  width: 700px;
  height: 400px;
  margin: 30px;
  border-radius: 20px;
  display: inline-block;
}
</style>
