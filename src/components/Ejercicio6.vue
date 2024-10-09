<template lang="">
    <div>
        <h1>6.-  Enlace dinámico al atributo href de un enlace</h1> 
        <p>Enunciado: Crea un componente que tenga un enlace (a) donde el href sea dinámico. El valor del enlace debe estar en el data del componente y cambiarse mediante v-bind.</p>
        <a v-bind:href='enlace' target="_blank">Re: Zero</a>
</div>
</template>
<script>
export default {
    name: 'enlaceDinamico',
    data(){
        return{
            enlace: 'https://www.crunchyroll.com/es/series/GRGG9798R/rezero--starting-life-in-another-world-'
        }
    }
}
</script>
<style lang="">
    
</style>