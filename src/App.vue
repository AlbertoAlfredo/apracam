<script setup>
import { RouterLink, RouterView } from 'vue-router'
import HelloWorld from '@/components/HelloWorld.vue'
</script>

<template>
  <header>
    <img alt="Vue logo" class="logo" src="@/assets/logo.svg" width="125" height="125" />

    <div class="wrapper">
      <nav>
        <RouterLink to="/">Home</RouterLink>
        <RouterLink to="/about">About</RouterLink>
      </nav>
    </div>
  </header>

  <RouterView />
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



@media (min-width: 1024px) {
  
}
</style>
