<template>
    <div>
        <h1>5.-  Textarea con descripción</h1>
        <p>Enunciado: Crea un componente que tenga un textarea donde el usuario pueda escribir una descripción. Muestra la descripción introducida en tiempo real en un párrafo debajo del textarea.</p>
        <textarea id="descripcion" v-model="descripcion" placeholder="Describe algo" rows="4" cols="100"></textarea>
        <p>Descripcion: {{ descripcion }}</p>

    </div>
</template>
<script>
export default {
    name: "textarea",
    data(){
        return{
            descripcion: ''
        }
    }
}
</script>
<style lang="">
    
</style>