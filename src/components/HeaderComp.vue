<script>
export default {
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
    <a href="#"> <h1>ULTRAPORTAL</h1></a>
    <div class="header-direita">
      <a href="#sobre"> Sobre</a>
      <a href="#strats">Estratégias</a>
      <a href="#speeds">Speedruns</a>
    </div>
  </header>
</template>
<style scoped>
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
