<template>
  <footer class="rodape">
      Desenvolvido por Douglas Taylor via Projeto Alura | 2024 - Projeto fictício sem fins comerciais.
  </footer>
</template>

<script lang="ts">
export default {

}
</script>

<style scoped>
.rodape {
  background: var(--verde-escuro, #263A29);
  padding: 1.5rem 7.5rem;
  display: flex;
  justify-content: center;
  align-items: center;
}

@media only screen and (max-width: 1300px) {
  .rodape {
    padding: 1.5rem 2.75rem;
  }
}
@media only screen and (max-width: 425px) {
  .rodape {
    padding: 1.5rem;
    text-align: center;
  }
}
</style>