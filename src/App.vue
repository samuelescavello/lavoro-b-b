<template>
    <div class="container">
      <HeaderComponent />
  </div>
  <MainComponent />
  
  
</template>

<script>
  import { store } from './store';
  import HeaderComponent from './components/HeaderComponent.vue';
  import MainComponent from './components/MainComponent.vue';
  export default {
    components: {
      HeaderComponent,
      MainComponent
    },
    name: 'App',
  }
</script>

<style lang="scss" scoped>
  .container {
    margin: 0 auto;
  }
</style>