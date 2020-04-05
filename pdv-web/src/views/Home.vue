<template>
  <section>
    <h1>Compre ou Venda</h1>
    <ProdutosBuscar />
    <ProdutosListar />
  </section>
</template>

<script>
// @ is an alias to /src
import ProdutosListar from "../components/ProdutosListar.vue";
import ProdutosBuscar from "../components/ProdutosBuscar.vue";

export default {
  name: "Home",
  components: { ProdutosListar, ProdutosBuscar }
};
</script>

<style scoped>
h1 {
  color: #87f;
  margin-top: 40px;
  font-size: 2rem;
  text-align: center;
}
</style>
