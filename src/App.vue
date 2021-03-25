<template>
  <div id="app">
    <!-- Muestro el componente 'Datos' en el template de 'App.vue' -->
    <Datos/>
  </div>
</template>
 
<script>
 
// Importo el componente 'Datos' 
import Datos from './components/Datos.vue'
 
export default {
  name: 'App',
  components: {
    Datos
  }
}
</script>
