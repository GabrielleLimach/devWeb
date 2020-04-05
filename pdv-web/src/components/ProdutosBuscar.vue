<template>
  <form>
    <input type="text" name="busca" id="busca" v-model="busca" />
    {{ busca }}
  </form>
</template>

<script>
export default {
  data() {
    return {
      busca: "",
    };
  },
  name: "ProdutosBuscar",
};
</script>
<style scoped></style>
