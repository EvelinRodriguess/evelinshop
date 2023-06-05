<script setup>
import MeuCarrinho from '@/components/MeuCarrinho.vue'
import ListagemLivros from '@/components/ListagemLivros.vue'
</script>

<template>
  <h1>Minha livraria</h1>
  <div class="container-geral">
    <listagem-livros />
    <meu-carrinho />
  </div>
</template>

<style scoped>
@import url('https://fonts.googleapis.com/css2?family=Bruno+Ace+SC&family=Press+Start+2P&display=swap');
.container-geral {
  /* display: flex;
  justify-content: space-between; */
  display: grid;
  grid-template-columns: 3fr 1fr;
}
h1 {
  font-family: 'Bruno Ace SC', cursive;
  align-items: center;
}
</style>
