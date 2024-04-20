<script setup lang="ts">
// import TodoList from "./components/TodoList.vue";
import contar from  './contar.vue';



</script>

<template>



  <div class="app-wrapper">
    <h1>Mi blog</h1>
    <div class="imagen">
      <img alt="Vue logo" class="logo" src="./assets/mary.jpg" />
    </div>
    <div class="descrip">
      <h2>María Mercedes Robelo Brenes</h2>
      <h2>Carnet: 20-01866-1</h2>
    </div>
    <h3>Incrementa tus puntos</h3>
    <div class="wrapper">
      <contar />
    </div>
    <div class="content">

      <img class="corinto" src="./assets/Nagarote_Nicaragua.jpg" alt="Imagen de Nagarote"
        title="Nagarote Leon Nicaragua">
      <h3>Nagarote (Camino de los Nagrandanos) es un municipio del departamento de León en la República de Nicaragua.
      </h3>

      <p>Es reconocido como "Municipio Azul" siendo municipio modelo destacado en la gestión ambiental y desde hace
        décadas es considerado "el más limpio de Nicaragua".</p>

      <h3>Toponimia</h3>
      <p>Según algunos autores, el origen del nombre de "Nagarote" es chorotega y significa "en el camino de los
        Nagrandanos", de las voces "Nagrand" - "Nagrandanos" y “Otli” - "camino".
        Otros investigadores afirman que se deriva de los vocablos "Nahualli – Otli" y se traduce como "camino de
        brujos".</p>


      <h3>Geografía</h3>
      <p>
        Se ubica en el departamento de León a una extensión de 598.4 km², está ubicada entre las coordenadas 12° 16′ 3″
        de latitud norte y 86° 33 55″ de longitud oeste, a una altitud de 86 m s. n. m.

        Sus límites geográficos son:

        al norte con el municipio de La Paz Centro y el Lago Xolotlán
        al sur con el municipio de Villa El Carmen
        al este con el municipio de Mateare
        al oeste con el Océano Pacífico.
        Historia
        El lugar fue conocido desde antes de la conquista española por su antiquísimo árbol de genízaro el cual, según
        se cree, vivió casi 800 años, hasta que fue impactado por un rayo y se decidió preservarlo en el Museo
        municipal, con su tronco y ramas se elaboraron utensilios decorativos que son exhibidos en dicho museo.

        Se ubicó en el cacicazgo de Imabite, sobre una llanura costera lindante con el océano Pacífico y el lago
        Xolotlán, las montañas de Matiari (actual Mateare) y la encomienda de León Viejo (hoy La Paz Centro), a orillas
        de la cordillera de los Marrabios.

        Esta llanura estaba enriquecida con pequeñas fuentes de agua dulce (vertientes) y de ríos pequeños que
        permanecían hasta en épocas de verano con mucha agua. Entre estos ríos se destacan los conocidos hoy, o fueron
        conocidos con los nombres de: El Pital, Soledad, Patastule, San Antonio, El Caimito, Las Tranquitas, El Obraje,
        Dos Ríos, San Luis, San Pedro, Palo de Sangre, Naranjo, Santiago y Sayulapa.

        En documento histórico de 1548, Nagarote aparece mencionado como encomienda del rey de España.

        Su primera iglesia fue erigida en 1650, con el nombre de "Santiago de La Concepción" de la villa de Nagarote.

        Fue elevado a rango de ciudad por Ley legislativa del Congreso Nacional de Nicaragua el 4 de junio de 1963.

        Nagarote tuvo antiguamente un floreciente puerto marítimo llamado Puerto Sandino. Este puerto fue atacado en
        1983, con mucha destrucción de las instalaciones que efectivamente destruyeron el puerto.</p>

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

