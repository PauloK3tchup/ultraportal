<script>
// import { RouterLink, RouterView } from 'vue-router'
import VideoBackground from 'vue-responsive-video-background-player'

export default {
  components: {
    VideoBackground
  },
  data() {
    return {
      view: {
        topOfPage: true
      }
    }
  },
  beforeMount() {
    window.addEventListener('scroll', this.handleScroll)
  },
  methods: {
    handleScroll() {
      if (window.pageYOffset > 0) {
        if (this.view.topOfPage) this.view.topOfPage = false
      } else {
        if (!this.view.topOfPage) this.view.topOfPage = true
      }
    }
  }
}
</script>

<template>
  <header :class="{ onScroll: !view.topOfPage }">
    <h1>ULTRAPORTAL</h1>
    <!-- 
    <div class="wrapper">
      <nav>
        <RouterLink to="/">Home</RouterLink>
        <RouterLink to="/about">About</RouterLink>
      </nav>
    </div> -->
    <div class="header-direita">
      <a href="">Sobre</a>
      <a href="">Estratégias</a>
      <a href="">Speedruns</a>
    </div>
  </header>
  <body>
    <video-background
      src="../src/assets/ultravideo.mp4"
      overlay="linear-gradient(0deg,#000000,#fb949e6b)"
      style="max-height: 600px; height: 500vh"
    >
      <h1 class="dentro">ULTRAPORTAL</h1>
      <h3 class="dentro">Aprenda e decimar o inferno com eSSStilo!</h3>
    </video-background>
    <RouterView />
  </body>
  <footer></footer>
</template>

<style scoped>
body {
  margin: 0;
  padding: 0;
  background-color: rgb(0, 0, 0);
  color: white;
  overflow-x: hidden;
}

h1.dentro {
  font-family: BroshK;
  font-size: 10rem;
  color: white;
  text-align: center;
  margin-top: 45vh;
}

header {
  background-color: #00000000;
  color: white;
  padding-left: 1rem;
  padding-right: 1rem;
  padding-top: 15px;
  padding-bottom: 10px;
  display: flex;
  justify-content: space-between;
  align-items: center;
  position: fixed;
  width: 100%;
  top: 0;
  transition: 0.25s;
  z-index: 1;
}

header.onScroll {
  background-color: #000;
}

h1 {
  font-family: BroshK;
  font-size: 3rem;
  margin-left: 5px;
}

a {
  color: white;
  text-decoration: none;
  margin: 0 1rem;
  font-family: VCR;
  padding: 10px;
  transition: 0.15s;
  border-radius: 5px;
}
a:hover {
  color: rgb(0, 0, 0);
  background-color: white;
  transform: scale(1.2);
}
a:active {
  color: white;
  background-color: black;
  transform: scale(0.9);
}
</style>
