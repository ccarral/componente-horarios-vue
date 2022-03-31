<template>
    <horarios-item></horarios-item>
</template>

<script>
import HorariosItem from './components/HorariosItem.vue'

export default {
    name: 'App',
    components: {
        HorariosItem
    }
}
</script>

<style>
#app {
    font-family: Avenir, Helvetica, Arial, sans-serif;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    text-align: center;
    color: #2c3e50;
    margin-top: 60px;
}
</style>
