<template>
    <div id="div1">
        <h1>Este es un nuevo componente</h1>
        <h2>{{ subtitulo }}</h2>
    </div>
</template>

<script>
    export default {
        name: 'Testcomponent',
        data(){
            return {
                subtitulo: 'Subtitulo'
            }
        }
    }
</script>