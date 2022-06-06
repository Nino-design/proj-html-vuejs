<template>
  <div id="app">
  <AppHeader/>
  <AppMain/>
  <AppFooter :icons1="footerIcons" :icons2="footerIcons2"/>

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
},
data: function () {
    return {
       footerIcons: [
        {
          text: "Start here",
        },
        {
          text: "Blog",
        },
        {
          text: "About us",
        },
        {
          text: "Success story",
        },
        {
          text: "Courses",
        },
        {
          text: "Contact us",
        },
      ],
      footerIcons2: [
        {
          text: "Merbership",
        },
        {
          text: "Purchase guide",
        },
         {
          text: "Privacy policy",
        },
         {
          text: "Terms of services",
        },
      ],
    };
  },

}
</script>

<style lang="scss">
@import "./style/common.scss";
</style>
