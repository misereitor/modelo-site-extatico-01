<template>
  <footer>
      <div class="footer">
        <div class="info">Modelo</div>
        <div class="direitos">Todos os direitos reservados</div>
      </div>
  </footer>
</template>

<script>
export default {
    name: "Footer"
}
</script>

<style scoped>
footer {
    bottom: 0;
    height: 120px;
    background-color: rgb(32, 32, 32);
    width: 100%;
}

.footer {
    display: flex;
    justify-content: space-evenly;
    align-items: center;
    color: rgb(179, 194, 195);
    height: inherit;
}
</style>