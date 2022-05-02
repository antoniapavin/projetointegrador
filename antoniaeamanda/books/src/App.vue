<script>
import PerfilBook from "@/components/PerfilBook.vue";
import ListaFavoritos from "@/components/ListaFavoritos.vue";
import ConteudoBook from "@/components/ConteudoBook.vue";
export default {
  components: { PerfilBook, ListaFavoritos, ConteudoBook },
};
</script>

<template>
  <PerfilBook />
  <ListaFavoritos />
  <ConteudoBook />
</template>
