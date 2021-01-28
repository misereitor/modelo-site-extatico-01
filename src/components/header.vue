<template>
  <header>
      <div class="header">
        <div class="img-logo">
            <img src=".././assets/home.svg" alt="Empresa">
        </div>
        <div class="menu">
            <a href="#">Home</a>
            <a href="#">Empresa</a>
            <a href="#">Produtos</a>
            <a href="#">Contatos</a>
        </div>
      </div>
  </header>
</template>

<script>
export default {
    name: "Header"
}
</script>

<style scoped>
header {
    height: 70px;
    background-color: rgb(32, 32, 32);
}

.header {
    display: flex;
    justify-content: space-between;
    align-items: center;
    max-width: 1100px;
    margin: auto;
    height: inherit;
}

.img-logo img{
    width: 90px;
    background-color: rgb(179, 194, 195);
    border-radius: 7px;
}

.menu a{
    text-decoration: none;
    color: rgb(233, 229, 229);
    margin-left: 15px;
}
</style>>