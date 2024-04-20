<script setup lang="ts">
// import TodoList from "./components/TodoList.vue";
import contar from  './contar.vue';



</script>

<template>

<h2>en desarrollo</h2>

  <div class="app-wrapper">
    <h1>Mi blog</h1>
    <div class="imagen">
      <img alt="Vue logo" class="logo" src="./assets/mary.jpg" />
    </div>
    <div class="descrip">
      <h2>Maria Rosa Brenes</h2>
      <h2>Carnet: 21--1</h2>
    </div>
    <h3>Incrementa tus puntos</h3>
    <div class="wrapper">
      <contar />
    </div>
   
  </div>
</template>

<style scoped>
.app-wrapper {
  margin-top: 0cap;
  height: 50%;
  width: 100%;
  background-color: rgb(244, 27, 139);
  display: flex;
  flex-direction: column;
  align-items: center;
}

.logo {
  display: block;
}

@media (min-width: 1024px) {
  header {
    display: flex;
    place-items: center;
    padding-right: calc(var(--section-gap) / 2);
  }

  header .wrapper {
    display: flex;
    place-items: flex-start;
    flex-wrap: wrap;
  }
}
.descrip{
  background-color: rgb(255, 255, 255);
  width: 100%;
}
.wrapper{
  justify-content: center;
  background-color: antiquewhite;
  width: 100%;
}
h3 {
  color: rgb(8, 8, 8);
}
.imagen {
  background-size: contain;
  margin-top: 5%;
  margin-bottom: 5%;
}
.corinto{
  background-position: 0%;
  margin-top: 10%;
  margin-bottom: 2%;
}
.lat{
  background-color: aqua;
}
h2{
  color:rgb(3, 2, 2);
}
p{
  color: black;
  justify-content: center;
}
.content{
  margin:1rem;
  
}
h1{
  color: rgb(18, 0, 108);
}
</style>

