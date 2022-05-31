<template>
  <div id="app">
  <AppHeader/>
  <AppMain/>
  <AppFooter/>

  </div>
</template>

<script>
import AppHeader from './components/AppHeader.vue';
import AppMain from './components/AppMain.vue';
import AppFooter from './components/AppFooter.vue';


export default {
  name: 'App',
  components: {
    AppMain,
    AppFooter,
    AppHeader
}
}
</script>

<style lang="scss">
@import "./style/common.scss";
</style>
