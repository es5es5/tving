<template>
  <div id="app">
    <Top></Top>
    <router-view/>
  </div>
</template>

<script>
import Top from './components/Top'

export default {
  name: 'App',
  components: {
    Top
  }
}
</script>

<style lang="scss">
@import 'colony-vue/src/assets/scss/reset.scss';
</style>
