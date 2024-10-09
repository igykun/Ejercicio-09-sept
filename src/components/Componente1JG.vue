<template>
    <div>
      <img :src="imageSrc" alt="Img" />
    </div>
  </template>
  
  <script>
  export default {
    data() {
      return {
        imageSrc: 'https://i.pinimg.com/474x/78/7d/d9/787dd92efa53d2a0c355d4a47a91850a.jpg'
      };
    },
  };
  </script>
  


<!-- 7.-  Enlace dinámico al atributo src de una imagen
Enunciado: Crea un componente que muestre una imagen con un src dinámico. El enlace de la imagen debe estar almacenado en el data del componente y cambiarse mediante v-bind.
 -->