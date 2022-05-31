<template>
  <div>
  <AppBanner/>
  <AppCourses/>
  <AppTutoring/>
  </div>
</template>

<script>
import AppBanner from './AppBanner.vue';
import AppCourses from './AppCourses.vue';
import AppTutoring from './AppTutoring.vue';
export default {
name:'AppMain',
components: {
  AppBanner,
  AppCourses,
  AppTutoring,
}
}
</script>

<style lang="scss" scoped>

</style>