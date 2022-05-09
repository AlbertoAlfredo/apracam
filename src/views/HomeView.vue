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
            <img style="width: 4vw; margin: 0 1vw;" src="@/assets/img/ICONES/ATENDENTE.png" alt="Icone de atendente">
            <p>Quer saber mais?<br/>Fale com um consultor</p>
          </div>
          <div style="width: 2vw"></div>
          <div class="flex-container">
            <img style="width: 4vw; margin: 0 1vw;" src="@/assets/img/ICONES/FEEDBACK.png" alt="Icone de feedback">
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
    <section>
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
    <section>
      <p>Pode se associar, Todo cidadão de bem, pessoa física ou jurídica que compreendam a importância e os benefícios dos derivados do <span>Cannabis</span></p>
      <p>O associado pode se enquadrar em três categorias de membros associados: MEMBROS BENEMÉRITOS, MEMBROS CONTRIBUINTES, MEMBROS SOCIAIS</p>
    </section>
    <section>
      <h2>VANTAGENS AO SER<br/> UM ASSOCIADO</h2>
      <div>
        <img src="" alt="">
        <p>Desconto em cursos</p>
      </div>
      <div>
        <img src="" alt="">
        <p>Acesso a informação segura e atualizada</p>
      </div>
      <div>
        <img src="" alt="">
        <p>Consulta médica com prescritores de cannabis</p>
      </div>
      <div>
        <img src="" alt="">
        <p>Inclusão nos grupos de pacientes para troca de experiência</p>
      </div>
      <div>
        Mensalidade será paga via internet no valor de R$30,00 ou R$50,00 (valor para associar-se na APRACAM). Todo Membro Contribuinte receberá uma carteirinha de associado com número de matrícula e dados pessoais.
      </div>
      <div>ASSOSSIECE AGORA</div>
    </section>
    <section>
      <div><img src="" alt=""></div>
      <div>
        <h2>Conheça Depoimentos de quem já se tornou nosso Associado.</h2>
        <img src="" alt="">
        <p>‘’Depois que me associei ao Apracam, obtive diversos beneficio e melhorei bastante, e conseguir aprender com os outros associados a melhor forma e beneficio que o cannabis pode trazer.’’</p>
        <p><span>Fernando Luiz</span><br/><span>Associado desde 2019</span></p>
      </div>
    </section>
    <section>
      <div>
        <h2>Preencha o formulário e receva o contado da nossa Equipe</h2>
        <p>Não se preocupe, o nosso contato é sem compormisso. Você só irá se tornar nosso um de nossos associados se for benéfico para você.</p>
      </div>
      <div>
        <form>
          <label for="celular">First name:</label>
          <input type="tel" id="celular" name="celular"><br/>
          <label for="nome">First name:</label>
          <input type="text" id="nome" name="nome"><br/>
          <label for="email">First name:</label>
          <input type="email" id="email" name="email"><br/>
          <button>Receber contato da Equipe</button>
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
  
</style>
<style>
.text-banner{
    color: #fff;
    font-size: 2.4vw;
    line-height: 1;
    padding: 4vw;
    text-align: justify;
    text-justify: inter-word;
  }
  .text-banner h2{
    font-weight: bold;
  }
  .text-banner-green{
    color: var(--vt-green1);
    font-size: 4vw;
    font-weight: bolder;
    line-height: 1;
    padding: 4vw 0;
    text-align: justify;
    text-justify: inter-word;
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
</style>
