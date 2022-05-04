<template>
  <div id="app">
    <JumboTron/>
  </div>
</template>

<script>
import JumboTron from './components/JumboTron.vue'

export default {
  name: 'App',
  components: {
    JumboTron
  }
}
</script>

<style lang="scss">
  @import './style/general.scss';
</style>
