<template>
    <div>
      <button 
        :class="{'active-class': isActive}" 
        @click="isActive = !isActive">
        Cambiar Clase
      </button>
    </div>
  </template>
  
  <script>
  export default {
    data() {
      return {
        isActive: false // Estado inicial del botón
      };
    }
  };
  </script>
  
  <style scoped>
  .active-class {
    background-color: green;
    color: white;
  }
  </style>
  