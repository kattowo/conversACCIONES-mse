<script setup>
// This starter template is using Vue 3 <script setup> SFCs
// Check out https://v3.vuejs.org/api/sfc-script-setup.html#sfc-script-setup
//import HelloWorld from './components/HelloWorld.vue'
import Cabecera from './components/Cabecera.vue';
import Preguntas from './components/Preguntas.vue'
import Respuesta from './components/Respuesta.vue';
import Respuesta2 from './components/Respuesta2.vue';
import MeComprometo from './components/Me-comprometo.vue';
import TeComprometes from './components/TeComprometes.vue';
import PreguntasFrecuentes from './components/PreguntasFrecuentes.vue';
import Paquetes from './components/Paquetes.vue';
import Footter from './components/footter.vue';
</script>

<template>
   <Cabecera/>
   <Preguntas/>
   <Respuesta/>
   <Respuesta2/>  
   <MeComprometo/>
   <TeComprometes/> 
   <PreguntasFrecuentes/>
   <Paquetes/>
   <Footter/>

  <!--<HelloWorld1 msg="Hello Vue 3 + Vite" />-->

</template>

<style>
*{
  padding: 0;
  margin: 0;
}
#app {
  font-family: 'Noto Sans', sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  /*color: #2c3e50;
  margin-top: 60px;*/
  overflow-x: hidden;
}

:root {
  --main-color: #c50050;
  --main-color2: #fff;
  --hover-btn: #ff1070;
}
</style>
