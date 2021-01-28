<template>
  <div class="conteiner">
      <div class="logo" style=""></div>
      <div class="produtos-destaque">
          <div class="produto">
              <h3>Produto 01</h3>
              <p>Perfeito para todas as horas</p>
          </div>
          <div class="produto">
              <h3>Produto 02</h3>
              <p>Perfeito para todo momento</p>
          </div>
          <div class="produto">
              <h3>Produto 03</h3>
              <p>Perfeito em qualquer horas</p>
          </div>
      </div>
      <div class="info">
          <h1>NOME DA EMPRESA</h1>
          <p>Pioneira na região com seus diversos produtos</p>
      </div>
      <div class="empresa-detalhes">
          <div class="info-empresa">
            <h3>Trabalhamos para melhor lhê atender!</h3>
            <p>Com os nosso profissionáis preparados para atender a sua demanda com maestria, focado na satisfação dos nosso clientes!</p>
          </div>
          <div class="info-empresa">
            <h3>Nosso produtos é de ótima qualidade!</h3>
            <p>Feita com material de ponta para resistir as maiores desafios do dia a dia!</p>
          </div>
          <div class="info-empresa">
            <h3>Com tudo, sua opinião é válida!</h3>
            <p>Ficamos muitos feliz com sua avaliação, tendo isso em mente, estamos sempre melhorando nosso atendimento!</p>
          </div>
      </div>
  </div>
</template>

<script>
export default {
    name: "Conteiner"
}
</script>

<style scoped>
.conteiner {
    widows: 100%;
}

.logo {
    background-color: rgb(117, 117, 117);
    height: calc(100vh - 230px);
    background-size: cover;
    background-repeat: no-repeat;
    background-image:url(.././assets/home.svg);
    background-position: top;
    background-attachment: fixed;
}

.produtos-destaque {
    display: flex;
    justify-content: space-evenly;
    max-width: 1000px;
    margin: calc((-100vw / 8) / 1.3) auto calc((-100vw / 8) / 4) auto;
}

.produto {
    width: calc(100vw / 8);
    height: calc(100vw / 8);
    background-color: aquamarine;
    text-align: center;
    font-size: 1.1rem;
}

.produto h3 {
    padding-top: 25px;
    margin-bottom: 25px;
} 

.info {
    height: 300px;
    background-color: rgb(158, 158, 158);
    color: rgb(255, 255, 255);
    text-align: center;
}

.info h1 {
    padding-top: 140px;
    margin-bottom: 30px;
    font-size: 2.3rem;
}

.info p {
    font-size: 1.3rem;
}

.empresa-detalhes {
    background-color: rgb(117, 117, 117);
    height: 350px;
}

.empresa-detalhes .info-empresa:first-child {
    padding-top: 60px;
}

.empresa-detalhes .info-empresa {
    text-align: center;
    margin: 0 auto 60px auto;
    max-width: 1000px;
}
</style>