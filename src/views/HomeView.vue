<script setup>
import UltraVideo from '../components/VideoComp.vue'
</script>

<template>
  <main>
    <UltraVideo />
    <a class="anchor" id="sobre"></a>
    <div class="container-fluid">
      <div class="artigo">
        <img class="esquerda" src="../assets/Ultrakill_cover.png" alt="" />
        <p>
          ULTRAKILL é um jogo de ação FPS criado por Arsi "Hakita" Patala e distribuído pela New
          Blood Interactive.
        </p>
      </div>
      <div class="foto">
        <img class="direita" src="../assets/tenebre-rosso-sangue-capa.jpg" alt="" />
      </div>
    </div>
  </main>
</template>
<style scoped>
div.artigo {
  margin: 35px;
  padding: 20px;
  background-color: #800000;
  border-radius: 10px;
  margin-top: 100px;
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
