<template>
  <main>
    <section id="banner">
      <div class="text-banner">
      <h2>ASSOCIAÇÃO PARANAENSE <br/> DE APOIO A CANABIS <br/> MEDINAL - APRACAM</h2>
      <h3>Conheça os benefícios que o auto cultivo do cnabis<br/> medicinal pode trazer e agregar na qualidade de vida</h3>
      <div class="flex-container">
        <RouterLink to="/associate">
          <div style="
            background-color: #fff;
            color: var(--vt-green1);
            border: #fff solid;
            margin: 2vw 0;
            padding: 1vw 3vw;
            border-radius: 10px;
            font-weight: bold;
          " >Conhecer<br/>o Cannabis</div>
        </RouterLink>
        <RouterLink to="/associate">
          <div style="
            background-color: #fff0;
            color: #fff;
            border: #fff solid;
            margin: 2vw;
            padding: 1vw 3vw;
            border-radius: 10px;
            font-weight: bold;
          " >Torna-se<br/>um Associado</div>
        </RouterLink>
        </div>
        </div>
        <div class="container-fluid flex-container" style="justify-content: end;">
          <div
        style="
          background-image: linear-gradient(to right, var(--vt-green3) , var(--vt-green4));
          top: 2vw;
          padding: 2vw;
          width: 50%;
          font-size: 1vw;
          border-radius: 0 0 0 40px ;
          color: #fff;
        "
        class="flex-container">
          <div class="flex-container">
            <img style="width: 4vw; height: 4vw; margin: 0 1vw;" src="@/assets/img/ICONES/ATENDENTE.png" alt="Icone de atendente">
            <p>Quer saber mais?<br/>Fale com um consultor</p>
          </div>
          <div style="width: 2vw"></div>
          <div class="flex-container">
            <img style="width: 4vw; height: 4vw; margin: 0 1vw;" src="@/assets/img/ICONES/FEEDBACK.png" alt="Icone de feedback">
            <p>Nossos Feedback<br/>O que estão falando</p>
          </div>
        </div>
        </div>
        
      
    </section>
    <hr>
    <section class="container">

        <h2 class="text-banner-green">QUEM SOMOS</h2>
        <p>Somos a ASSOCIAÇÃO PARANAENSE DE APOIO A CANNABIS MEDICINAL (APRACAM), fundada em 10 de dezembro de 2019 e registrada em 19 de fevereiro de 2020 no município de Umuarama, Paraná, Brasil, inscrita no CNPJ: 36.716.085/0001-56. Surgimos pela demanda emergente local de prover os benefícios medicinais da Cannabis para a população que necessita. </p>

    </section>
    <section style="margin: 8vw 0;">
      <img src="@/assets/img/visao.png" alt="Nossa Visao"
        style="width: 100%;"
      >
      <!-- <div>
        <img style="width: 4vw;" src="@/assets/img/ICONES/FEEDBACK.png" alt="Icone de feedback">
        <h2>MISSÃO</h2>
        <p>Agregar melhoria na qualidade de vida das pessoas, informar sobre o direito ao auto cultivo,..</p>
      </div>
      <div>
        <img style="width: 4vw;" src="@/assets/img/ICONES/FEEDBACK.png" alt="Icone de feedback">
        <h2>VISÃO</h2>
        <p>Tornar-se referência em Cannabis medicinal no Brasil. Abranger todas as vertentes que a Cannabis está envolvida. Contemplar uma produção de Cannabis medicinal </p>
        <div>Saber mais</div>
      </div>
      <div>
        <img style="width: 4vw;" src="@/assets/img/ICONES/FEEDBACK.png" alt="Icone de feedback">
        <h2>VALORES</h2>
        <p>Trabalho sério, honestidade, justiça, respeito à natureza, cumprir com a constituição nacional, sustentab... </p>
      </div> -->
    </section>
    <section id="banner2" class="text-banner">
      <h2 style="text-align: center; margin-bottom: 4vw;">Pode se associar, Todo cidadão<br/> de bem, pessoa física ou jurídica<br/> que compreendam a importância<br/> e os benefícios dos derivados<br/> do <span style="color: var(--vt-green1); background-color: #fff;">Cannabis</span></h2>
      <p style="font-size: 2vw;">O associado pode se enquadrar em três categorias de membros associados: <b>MEMBROS BENEMÉRITOS, MEMBROS CONTRIBUINTES, MEMBROS SOCIAIS</b></p>
    </section>
    <section class="container">
      <h2 class="text-banner-green">VANTAGENS AO SER<br/> UM ASSOCIADO</h2>
      <div class="flex-container cards">
        <div class="card-green">
          <img src="@/assets/img/ICONES/DESCONTO.png" alt="">
          <p>Desconto em cursos</p>
        </div>
        <div class="card-green">
          <img src="@/assets/img/ICONES/INFORMACAO.png" alt="">
          <p>Acesso a informação segura e atualizada</p>
        </div>
        <div class="card-green">
          <img src="@/assets/img/ICONES/MEDICO.png" alt="">
          <p>Consulta médica com prescritores de cannabis</p>
        </div>
        <div class="card-green">
          <img src="@/assets/img/ICONES/GRUPO.png" alt="">
          <p>Inclusão nos grupos de pacientes para troca de experiência</p>
        </div>
      </div>
      
      <div>
        Mensalidade será paga via internet no valor de R$30,00 ou R$50,00 (valor para associar-se na APRACAM). Todo Membro Contribuinte receberá uma carteirinha de associado com número de matrícula e dados pessoais.
      </div>
      <div style="display: flex;justify-content: center; margin: 2vw 0">
      <a href="#" class="botao">ASSOSSIACE AGORA</a>
      </div>
    </section>
    <section  class="flex-container flex-center container">
      <div><img style="width: 40vw;" src="@/assets/img/MENINO.png" alt=""></div>
      <div class="text-banner-green">
        <h2 style="font-size: 4vw">Conheça Depoimentos de quem já se tornou nosso Associado.</h2>
        <img src="@/assets/img/ICONES/DEPOIMENTO.png" style="background-color: var(--vt-green1); padding: 3%; border-radius: 20px; width: 7vw;" alt="">
        <p style="font-size: 2vw">‘’Depois que me associei ao Apracam, obtive diversos beneficio e melhorei bastante, e conseguir aprender com os outros associados a melhor forma e beneficio que o cannabis pode trazer.’’</p>
        <p style="font-size: 2vw; color: var(--vt-green1); font-weight: bold;">Fernando Luiz</p>
        <p style="font-size: 1.8vw;">Associado desde 2019</p>
      </div>
    </section>
    <section id="banner3" class="flex-container">
      <div class="text-banner" style="width: 45vw;">
        <h2>Preencha o formulário e receba o contado da nossa Equipe</h2>
        <p>Não se preocupe, o nosso contato é sem compromisso. Você só irá se tornar nosso um de nossos associados se for benéfico para você.</p>
      </div>
      <div class="container-form" style="
        background-color: #fff;
        padding: 6vw;
        border-radius: 100px;
        box-shadow: 10px 5px 5px #f9f9f938;
        color: #c5c5c5;
      ">
        <form class="formulario1">
          <label for="celular">Celular com DDD:</label><br/>
          <input type="tel" id="celular" name="celular" placeholder="(00) 0000-00000"><br/>
          <label for="nome">Seu Nome:</label><br/>
          <input type="text" id="nome" name="nome" placeholder="Nome e Sobrenome"><br/>
          <label for="email">Seu E-mail:</label><br/>
          <input type="email" id="email" name="email" placeholder="Seu e-mail"><br/>
          <button class="botao" style="font-size: 2vw;">Receber contato da Equipe</button>
        </form>
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
  #banner2{
    background-image: url('@/assets/img/BACKGROUD2.png');
    background-size: 100% auto ;
    width: 100%;
    min-height: 30vw;
    padding: 6vw 4vw;
  }
  #banner3{
    background-image: url('@/assets/img/BACKGROUD3.png');
    background-size: 100% auto ;
    width: 100%;
    min-height: 30vw;
    padding: 14vw 4vw 0 4vw ;
  }
  .card-green{
    align-items: center;
    text-align: center;
    margin: 0 2vw;
  }
  .card-green p{
    color: var(--vt-green1);
    font-weight: bold !important;
  }
  .card-green img{
    width: 25%;
    background-color: var(--vt-green1);
    padding: 3%;
    border-radius: 15px;
  }
  .botao{
    background-color: var(--vt-green1);
    color: #fff !important;
    font-size: 3vw;
    padding: 1vw;
    border-radius: 20px;
    width: fit-content;
    border: none;
  }
  @media (max-width: 400px) {
    .container-form{
      width: 80vw;
      border-radius: 10px !important;
      padding: 1vw !important;
      margin-bottom: 4vw; 
    }
    #banner3{
    background-image: url('@/assets/img/BACKGROUD1.png');
    background-size: cover;
  }
  };
</style>
<style>
.text-banner{
    color: #fff;
    font-size: 3vw;
    font-weight: bolder;
    line-height: 1;
    padding: 4vw;
  }
  .text-banner h2{
    font-weight: bold;
    color: #fff;
    font-size: 4vw;
  }
  .text-banner h2 span{
    font-size: 4vw;
  }
  .text-banner p, .text-banner a{
    color: #fff;
  }
  .text-banner-green{
    color: var(--vt-green1);
    font-size: 4vw;
    font-weight: bolder;
    line-height: 1;
    padding: 4vw 0;
  }
  .container{
    margin: 4vw 6vw;
  }
  .text-banner-green h2{
    font-weight: bold;
  }
  .container-fluid{
    width: 100%;
  }
  .formulario1{
    margin-bottom: 0px;
  }
  .formulario1 input{
    border: #00000020 solid;
    border-radius: 10px;
    width: 100%;
    font-size: 2vw;
    margin: 1vw 0;
  }
  .formulario1 input:focus, .formulario1 input:focus-visible, .formulario1 textarea:focus, .formulario1 textarea:focus-visible{
    border: var(--vt-green1) solid;
    outline: none;
  }
  .formulario1 label{
    font-weight: bold;
  }
</style>
