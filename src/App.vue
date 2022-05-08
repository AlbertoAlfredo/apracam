<script setup>
import { RouterLink, RouterView } from 'vue-router'
import HelloWorld from '@/components/HelloWorld.vue'
</script>

<template>
  <header style="margin-bottom: 1vw;">
    <h2
      style="text-align:center; color: #ccc;"
    >TORNE- SE UM ASSOCIADO HOJE MESMO E VENHA CONHECER TODOS OS BENEFICIOS DO CANNABIS</h2>
    <div class="wrapper">
      <nav class="flex-container flex-around" style="align-items: flex-end">
        <RouterLink to="/"><img alt="Apracam Logo" class="logo" src="@/assets/img/LOGO.png" width="200"/></RouterLink>
        <RouterLink class="link-header" to="/#quem-somos">QUEM SOMOS</RouterLink>
        <RouterLink class="link-header" to="/#associados">ASSOCIADOS</RouterLink>
        <RouterLink class="link-header" to="/#contato">CONTATO</RouterLink>
        <RouterLink class="link-header" to="/#mais-informacoes">MAIS INFORMAÇÕES</RouterLink>
        <RouterLink to="/associate">
          <div style="
            background-color: #AEDE00;
            color: #1E5A33;
            padding: 1vw 3vw;
            border-radius: 10px;
            font-weight: bold;
          " >TORNA-SE<br/>ASSOCIADO</div>
        </RouterLink>
      </nav>
    </div>
  </header>

  <RouterView />
  <footer class="flex-container flex-around" style="align-items: flex-end">
        <RouterLink to="/"><img alt="Apracam Logo" class="logo" src="@/assets/img/LOGO.png" width="200"/></RouterLink>
        <div>
          Nos acompanhe nas redes sociais
          Inscreva-se na nossa newsletter
        </div>
      </footer>
</template>

<style>
@import '@/assets/base.css';

@font-face {
  font-family: altone;
  src: url('@/assets/fonts/AltoneTrial-Regular.ttf');
  font-weight: normal;
}
@font-face {
  font-family: altone;
  src: url('@/assets/fonts/AltoneTrial-Bold.ttf');
  font-weight: bold;
}
@font-face {
  font-family: altone;
  src: url('@/assets/fonts/AltoneTrial-BoldOblique.ttf');
  font-weight: bold;
  font-style: oblique;
}
hr{
  border: none;
  height: 4vw;
}
 h1, p, div, a{
    font-family: altone;
  }

a{
  text-decoration: none !important;
  color: black;
}
.flex-container{
  display: flex;
}
.flex-around{
  justify-content: space-around;
}
.link-header{
  color: var(--vt-green1);
}

@media (min-width: 1024px) {
  
}
</style>
