<template>
    <div class="container">
      <HeaderComponent />
  </div>
  <MainComponent />
  <FooterComponet />

  
  
</template>

<script>
  import { store } from './store';
  import HeaderComponent from './components/HeaderComponent.vue';
  import MainComponent from './components/MainComponent.vue';
  import FooterComponet from './components/FooterComponent.vue';
  export default {
    components: {
      HeaderComponent,
      MainComponent,
      FooterComponet
    },
    name: 'App',
  }
</script>

<style lang="scss" scoped>
  .container {
    margin: 0 auto;
  }
</style>