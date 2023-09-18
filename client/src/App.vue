<template>
  <game-container></game-container>
</template>

<script>
import GameContainer from './components/GameContainer.vue'

export default {
  name: 'App',
  components: {
    'game-container': GameContainer
  }
}
</script>

<style>
#app {
  margin-top: 0;
}
</style>
