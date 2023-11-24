<template>
    <main class="text-light">
        <ChiComponent></ChiComponent>
        <!-- <h1>In questo punto ci sarà l'elemento di riferimento che l'utente cliccherà dal header.<br>Il punto di partenza sarà la pagina "chi sono".</h1> -->
    </main>
</template>
  
<script>
import ChiComponent from '../views/ChiComponent.vue';
export default {
    name: 'MainComponent',
    data() {
        return {

        }
    },
    methods: {

    },
    components: {
        ChiComponent
    },
    mounted() {

    }
}
</script>
  
<style lang="scss" scoped>
    main {
        background-color: rgba(58, 67, 94, 1);
    }
</style>