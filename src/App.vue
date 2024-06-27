<template>
  <div class="container">
    <Headercomponents />
    <Maincomponents />
  </div>
  
</template>

<script>
  import { store } from './store';
  import Headercomponents from './components/HeaderComponent.vue';
  import Maincomponents from './components/MainComponent.vue';
  export default {
    components: {
      Headercomponents,
      Maincomponents
    },
    name: 'App',
  }
</script>

<style lang="scss" scoped>
  .container {
    margin: 0 auto;
    margin-top: 20px;
  }
</style>