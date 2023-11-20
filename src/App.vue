<script>
// import { RouterLink, RouterView } from 'vue-router'
import HeaderComponent from './components/HeaderComponent.vue';
import MainComponent from './components/MainComponent.vue';
import FooterComponent from './components/FooterComponent.vue';
// import HelloWorld from './components/HelloWorld.vue';
export default {
  name: 'App',
  data() {
    return {

    }
  },
  methods: {

  },
  components: {
    HeaderComponent,
    MainComponent,
    FooterComponent
  },
  
  mounted() {

  }
}
</script>

<template>
  <HeaderComponent/>
  <MainComponent/>

</template>

<style lang="scss" scoped>

</style>
