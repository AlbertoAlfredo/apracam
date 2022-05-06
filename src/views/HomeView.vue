
<template>
  <main>
    <section id="banner">
      <h1>ASSOCIAÇÃO PARANAENSE <br/> DE APOIO A CANABIS <br/> MEDINAL - APRACAM</h1>
      <h2>Conheça os benefícios que o auto cultivo do cnabis<br/> medicinal pode trazer e agregar na qualidade de vida</h2>
      <div>
        <RouterLink to="/associate">
          <div style="
            background-color: #AEDE00;
            color: #1E5A33;
            padding: 1vw 3vw;
            border-radius: 10px;
            font-weight: bold;
          " >Conhecer<br/>o Cannabis</div>
        </RouterLink>
        <RouterLink to="/associate">
          <div style="
            background-color: #AEDE00;
            color: #1E5A33;
            padding: 1vw 3vw;
            border-radius: 10px;
            font-weight: bold;
          " >Torna-se<br/>um Associado</div>
        </RouterLink>
      </div>
    </section>
  </main>
</template>
<style scoped>
  #banner{
    background-image: url('@/assets/img/BACKGROUD1.png');
    background-size: cover;
    width: 100%;
    min-height: 30vw;
  }
</style>
