<template>
  <div id="app">
    <img src="./assets/logo.png">
    <Mohit></Mohit>
  </div>
</template>

<script lang="ts">
  import Vue from 'vue'
  import Component from 'vue-class-component'
  import Mohit from './components/Mohit.vue'

  @Component({
    components: { Mohit }
  })
  export default class App extends Vue {}
</script>
