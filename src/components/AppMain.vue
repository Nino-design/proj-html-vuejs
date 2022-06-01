<template>
  <div>
  <AppBanner/>
  <AppCourses/>
  <AppTutoring/>
  <AppReviews/>
  </div>
</template>

<script>
import AppBanner from './AppBanner.vue';
import AppCourses from './AppCourses.vue';
import AppTutoring from './AppTutoring.vue';
import AppReviews from './AppReviews.vue';
export default {
name:'AppMain',
components: {
  AppBanner,
  AppCourses,
  AppTutoring,
  AppReviews,
}
}
</script>

<style lang="scss" scoped>

</style>