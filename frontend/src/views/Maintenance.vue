<template>
  <b-container fluid class="vh-100">
    <b-row class="h-100 d-flex justify-content-center align-items-center">
      <b-col md="1"/>
      <b-col md="10">
        <transition-group appear name="fade">
          <b-img fluid style="max-width: 12rem; max
          -height: 16rem;" key="img" class="mt-n4"
          src="../assets/logo.svg"/>
          <h1 key="title" class="mt-2">Actualment el servei d'Isard es troba en manteniment</h1>
          <h2 key="text">El servei tornarà a estar disponible de 8:00h a 18:00h</h2>
          <h2 key="text2">Disculpeu les molèsties</h2>
        </transition-group>
      </b-col>
      <b-col md="1"/>
    </b-row>
  </b-container>
</template>

<script>
// @ is an alias to /src

export default {
}
</script>

<style scoped>
  .fade-enter-active, .fade-leave-active {
    transition: opacity 1s;
  }
  .fade-enter, .fade-leave-to {
    opacity: 0;
  }
</style>
